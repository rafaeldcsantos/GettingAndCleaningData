# Getting And Cleaning Data

This is the README file for my solution to the **Getting and Cleaning Data course project**.

There is a single R file on this repo: `run_analysis.R`. This R file performs the following actions:

1. Reads the feature names file `UCI HAR Dataset/features.txt`
2. Reads the train data from file `UCI HAR Dataset/train/X_train.txt` and use the feature names to name the columns in the train data set.
3. Reads the train subject from file `UCI HAR Dataset/train/subject_train.txt`, label its single column to "Subject" and convert it to factor.
4. Reads the train labels from file `UCI HAR Dataset/train/y_train.txt`, label its single column to "Activity", convert it to factor and set the factor levels to one of "WALKING","WALKING_UPSTAIRS","WALKING_DOWNSTAIRS","SITTING","STANDING","LAYING"
5. Concatenates (`cbind`) the three data sets into a `train` data set.
6. Do steps 2..5 for the test data sets (file names are `UCI HAR Dataset/test/X_test.txt`, `UCI HAR Dataset/test/subject_test.txt` and `UCI HAR Dataset/test/y_test.txt`).
7. Concatenate (`rbind`) the train and test data sets.

## Codebook

The project requirement asked to 



# -----------------------------------------------------------------------------
# Now with the data properly loaded and labeled let's see the questions.
# -----------------------------------------------------------------------------

# You should create one R script called run_analysis.R that does the following. 
# 1. Merges the training and the test sets to create one data set.
fullData <- rbind(train,test)

# 2. Extracts only the measurements on the mean and standard deviation for each measurement. 
# We can do that selecting all columns with names that contain mean or std.
# Remember to keep also columns Subject and Label! There are several ways to do this,
# I will save the indexes of the columns by name and use them for selection.
allNames <- colnames(fullData)
theOnesIWant <- grep("mean|std", allNames)
subjectIndex <- match("Subject",names(fullData))
labelIndex <- match("Activity",names(fullData))
selectedData <- fullData[c(theOnesIWant,subjectIndex,labelIndex)]

# 3. Uses descriptive activity names to name the activities in the data set
# We did that when we read the files :-) Column Activity is a proper factor too.

# 4. Appropriately labels the data set with descriptive variable names. 
# This is also vague -- variable names are already descriptive for me. 
# Let's expand the abbreviations and see how they look. 
# I've decided not to expand "std".
allNames <- colnames(selectedData)
allNames <- sub("Acc","Acceleration",allNames)
allNames <- sub("Mag","Magnitude",allNames)
allNames <- sub("Freq","Frequency",allNames)
allNames <- sub("Gyro","AngularVelocity",allNames)
allNames <- sub("^t","TimeDomain-",allNames)
allNames <- sub("^f","FrequencyDomain-",allNames)
allNames <- sub("\\(\\)","",allNames)
allNames
names(selectedData) <- allNames

# 5. From the data set in step 4, creates a second, independent tidy data set with the 
# average of each variable for each activity and each subject.
summary <-
  selectedData %>% group_by(Activity,Subject) %>% summarise_each(funs(mean))

# First item: Please upload your data set as a txt file created with write.table() using row.name=FALSE 
# (do not cut and paste a dataset directly into the text box, as this may cause errors saving your 
# submission).
write.table(summary,row.name=FALSE,file="result.txt")






 You should create one R script called run_analysis.R that does the following. 
Merges the training and the test sets to create one data set.
Extracts only the measurements on the mean and standard deviation for each measurement. 
Uses descriptive activity names to name the activities in the data set
Appropriately labels the data set with descriptive variable names. 
From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

Good luck!