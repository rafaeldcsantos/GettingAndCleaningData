# Getting And Cleaning Data

This is the README file for my solution to the **Getting and Cleaning Data course project**.

There is a single R file on this repo: `run_analysis.R`. This R file performs the actions described below.

## Data Loading

1. Reads the feature names file `UCI HAR Dataset/features.txt`
2. Reads the train data from file `UCI HAR Dataset/train/X_train.txt` and use the feature names to name the columns in the train data set.
3. Reads the train subject from file `UCI HAR Dataset/train/subject_train.txt`, label its single column to "Subject" and convert it to factor.
4. Reads the train labels from file `UCI HAR Dataset/train/y_train.txt`, label its single column to "Activity", convert it to factor and set the factor levels to one of "WALKING","WALKING_UPSTAIRS","WALKING_DOWNSTAIRS","SITTING","STANDING","LAYING"
5. Concatenates (`cbind`) the three data sets into a `train` data set.
6. Do steps 2..5 for the test data sets (file names are `UCI HAR Dataset/test/X_test.txt`, `UCI HAR Dataset/test/subject_test.txt` and `UCI HAR Dataset/test/y_test.txt`).
7. Concatenate (`rbind`) the train and test data sets.

## Data Selection
The project requirement asks to keep only the mean and standard deviation for each measurement. 
From the data documentation we see that only columns with the strings "mean" and "std" will be kept. Filtering with `grep` solves this.
For completeness we also keep the columns "Subject" and "Activity". 

## Data Annotation
The activity names were already loaded and attached to the data in step 4 of "Data Loading". 

## Codebook
There are 79 variables which names refer to either mean or average measures. These variables
are described in the `CodeBook.md` file.

## Final Data Product

The final data product is a table with averages for each variable for each activity and each subject.
This was done by grouping the data by "Activity" and "Subject" and summarizing each variable by the groups.
The results were written in the `result.txt` text file.
