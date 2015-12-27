# CodeBook

This file describes the variables in the data file `result.txt`, created by the script in `run_analysis.R`.

The variables were selected from the full set from the *Human Activity Recognition Using Smartphones Dataset*. 
Please read the file `README.txt` for more details on how they were measured. This code book describes only
the variable names and a generic, textual description.

Variable names were extended/made more descriptive as per requirements. Since there are several variations on the measures
that caused some long variable names.

## Variables in the Time Domain 

| Variable Name | Description | 
| --- | --- | 
| TimeDomain-BodyAcceleration-mean-X | Mean Body Acceleration on axis X | 
| TimeDomain-BodyAcceleration-mean-Y | Same for axis Y | 
| TimeDomain-BodyAcceleration-mean-Z | Same for axis Z | 
| TimeDomain-BodyAcceleration-std-X | Standard Deviation Acceleration on axis X | 
| TimeDomain-BodyAcceleration-std-Y | Same for axis Y | 
| TimeDomain-BodyAcceleration-std-Z | Same for axis Z | 
| TimeDomain-GravityAcceleration-mean-X | Mean Gravity Acceleration on axis X | 
| TimeDomain-GravityAcceleration-mean-Y | Same for axis Y | 
| TimeDomain-GravityAcceleration-mean-Z | Same for axis Z | 
| TimeDomain-GravityAcceleration-std-X | Standard Deviation Gravity Acceleration on axis X | 
| TimeDomain-GravityAcceleration-std-Y | Same for axis Y | 
| TimeDomain-GravityAcceleration-std-Z | Same for axis Z | 
| TimeDomain-BodyAccelerationJerk-mean-X | Mean Body Acceleration (Jerk) on axis X | 
| TimeDomain-BodyAccelerationJerk-mean-Y | Same for axis Y | 
| TimeDomain-BodyAccelerationJerk-mean-Z | Same for axis Z | 
| TimeDomain-BodyAccelerationJerk-std-X | Standard Deviation Body Acceleration (Jerk) on axis X | 
| TimeDomain-BodyAccelerationJerk-std-Y | Same for axis Y | 
| TimeDomain-BodyAccelerationJerk-std-Z | Same for axis Z | 
| TimeDomain-BodyAngularVelocity-mean-X | Mean Body Angular Velocity on axis X | 
| TimeDomain-BodyAngularVelocity-mean-Y | Same for axis Y | 
| TimeDomain-BodyAngularVelocity-mean-Z | Same for axis Z | 
| TimeDomain-BodyAngularVelocity-std-X | Standard Deviation Body Angular Velocity on axis X | 
| TimeDomain-BodyAngularVelocity-std-Y | Same for axis Y | 
| TimeDomain-BodyAngularVelocity-std-Z | Same for axis Z | 
| TimeDomain-BodyAngularVelocityJerk-mean-X | Mean Body Angular Velocity (Jerk) on axis X | 
| TimeDomain-BodyAngularVelocityJerk-mean-Y | Same for axis Y | 
| TimeDomain-BodyAngularVelocityJerk-mean-Z | Same for axis Z | 
| TimeDomain-BodyAngularVelocityJerk-std-X | Standard Deviation Body Angular Velocity (Jerk) on axis X | 
| TimeDomain-BodyAngularVelocityJerk-std-Y | Same for axis Y | 
| TimeDomain-BodyAngularVelocityJerk-std-Z | Same for axis Z | 
| TimeDomain-BodyAccelerationMagnitude-mean | Mean Magnitude for Body Acceleration | 
| TimeDomain-BodyAccelerationMagnitude-std | Standard Deviation Magnitude for Body Acceleration | 
| TimeDomain-GravityAccelerationMagnitude-mean | Mean Magnitude for Gravity Acceleration | 
| TimeDomain-GravityAccelerationMagnitude-std | Standard Deviation Magnitude for Gravity Acceleration | 
| TimeDomain-BodyAccelerationJerkMagnitude-mean | Mean Magnitude for Body Acceleration (Jerk) | 
| TimeDomain-BodyAccelerationJerkMagnitude-std | Standard Deviation Magnitude for Body Acceleration (Jerk) | 
| TimeDomain-BodyAngularVelocityMagnitude-mean | Mean Magnitude for Body Angular Velocity|
| TimeDomain-BodyAngularVelocityMagnitude-std | Standard Deviation Magnitude for Body Angular Velocity|
| TimeDomain-BodyAngularVelocityJerkMagnitude-mean | Mean Magnitude for Body Angular Velocity Jerk |
| TimeDomain-BodyAngularVelocityJerkMagnitude-std | Standard Deviation Magnitude for Body Angular Velocity Jerk|
 
## Variables in the Frequency Domain 
 
| Variable Name | Description | 
| --- | --- | 
| FrequencyDomain-BodyAcceleration-mean-X | Mean Body Acceleration on axis X | 
| FrequencyDomain-BodyAcceleration-mean-Y | Same for axis Y | 
| FrequencyDomain-BodyAcceleration-mean-Z | Same for axis Z | 
| FrequencyDomain-BodyAcceleration-std-X | Standard Deviation Acceleration on axis X | 
| FrequencyDomain-BodyAcceleration-std-Y | Same for axis Y | 
| FrequencyDomain-BodyAcceleration-std-Z | Same for axis Z | 
| FrequencyDomain-BodyAcceleration-meanFrequency-X | Mean Body Acceleration Frequency on axis X | 
| FrequencyDomain-BodyAcceleration-meanFrequency-Y | Same for axis Y | 
| FrequencyDomain-BodyAcceleration-meanFrequency-Z | Same for axis Z | 
| FrequencyDomain-BodyAccelerationJerk-mean-X | Mean Body Acceleration (Jerk) on axis X |
| FrequencyDomain-BodyAccelerationJerk-mean-Y | Same for axis Y | 
| FrequencyDomain-BodyAccelerationJerk-mean-Z | Same for axis Z | 
| FrequencyDomain-BodyAccelerationJerk-std-X | Standard Deviation Body Acceleration (Jerk) on axis X |
| FrequencyDomain-BodyAccelerationJerk-std-Y | Same for axis Y | 
| FrequencyDomain-BodyAccelerationJerk-std-Z | Same for axis Z | 
| FrequencyDomain-BodyAccelerationJerk-meanFrequency-X | Mean Body Acceleration (Jerk) Frequency on axis X |
| FrequencyDomain-BodyAccelerationJerk-meanFrequency-Y | Same for axis Y | 
| FrequencyDomain-BodyAccelerationJerk-meanFrequency-Z | Same for axis Z | 
| FrequencyDomain-BodyAngularVelocity-mean-X | Mean Body Angular Velocity on axis X |
| FrequencyDomain-BodyAngularVelocity-mean-Y | Same for axis Y | 
| FrequencyDomain-BodyAngularVelocity-mean-Z | Same for axis Z | 
| FrequencyDomain-BodyAngularVelocity-std-X | Standard Deviation Body Angular Velocity on axis X |
| FrequencyDomain-BodyAngularVelocity-std-Y | Same for axis Y | 
| FrequencyDomain-BodyAngularVelocity-std-Z | Same for axis Z | 
| FrequencyDomain-BodyAngularVelocity-meanFrequency-X | Mean Body Angular Velocity Frequency on axis X |
| FrequencyDomain-BodyAngularVelocity-meanFrequency-Y | Same for axis Y | 
| FrequencyDomain-BodyAngularVelocity-meanFrequency-Z | Same for axis Z | 
| FrequencyDomain-BodyAccelerationMagnitude-mean | Mean Body Acceleration Magnitude|
| FrequencyDomain-BodyAccelerationMagnitude-std | Standard Deviation Body Acceleration Magnitude|
| FrequencyDomain-BodyAccelerationMagnitude-meanFrequency | Mean Body Acceleration Frequency Magnitude|
| FrequencyDomain-BodyBodyAccelerationJerkMagnitude-mean | Mean Magnitude for Body Acceleration (Jerk) |
| FrequencyDomain-BodyBodyAccelerationJerkMagnitude-std | Standard Deviation for Body Acceleration (Jerk) |
| FrequencyDomain-BodyBodyAccelerationJerkMagnitude-meanFrequency | Mean Frequency Magnitude for Body Acceleration (Jerk) |
| FrequencyDomain-BodyBodyAngularVelocityMagnitude-mean | Mean Magnitude for Body Angular Velocity | 
| FrequencyDomain-BodyBodyAngularVelocityMagnitude-std | Standard Deviation Magnitude for Body Angular Velocity | 
| FrequencyDomain-BodyBodyAngularVelocityMagnitude-meanFrequency | Mean Frequency Magnitude for Body Angular Velocity | 
| FrequencyDomain-BodyBodyAngularVelocityJerkMagnitude-mean | Mean Magnitude for Body Angular Velocity Jerk |
| FrequencyDomain-BodyBodyAngularVelocityJerkMagnitude-std | Standard Deviation Magnitude for Body Angular Velocity Jerk |
| FrequencyDomain-BodyBodyAngularVelocityJerkMagnitude-meanFrequency | Mean Frequency Magnitude for Body Angular Velocity Jerk |
 
Please note that the last 9 variables contained "BodyBody" in their names in the original data. 
  
## Other Variables
 
For completeness, we preserved the data used to calculate the means per category combination. These are: 
 
| Variable Name | Description | 
| --- | --- | 
| Subject | Subject index (1..30) |
| Activity | One of "WALKING", "WALKING_UPSTAIRS", "WALKING_DOWNSTAIRS", "SITTING", "STANDING", "LAYING" |