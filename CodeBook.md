# CodeBook

This file describes the variables in the data file `result.txt`, created by the script in `run_analysis.R`.

The variables were selected from the full set from the *Human Activity Recognition Using Smartphones Dataset*. 
Please read the file `README.txt` for more details on how they were measured. This code book describes only
the variable names and a generic, textual description.

Variable names were extended/made more descriptive as per requirements. Since there are several variations on the measures
that caused some long variable names.

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
  | TimeDomain-GravityAcceleration-std-Z | Same for axis Z|                                 
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
  | TimeDomain-BodyAngularVelocityJerk-mean-Y |   Same for axis Y |                        
  | TimeDomain-BodyAngularVelocityJerk-mean-Z |     Same for axis Z |                       
  | TimeDomain-BodyAngularVelocityJerk-std-X |  Standard Deviation Body Angular Velocity (Jerk) on axis X |                            
  | TimeDomain-BodyAngularVelocityJerk-std-Y |   Same for axis Y |                         
  | TimeDomain-BodyAngularVelocityJerk-std-Z |  Same for axis Z |                           
  | TimeDomain-BodyAccelerationMagnitude-mean | Mean Magnitude for Body Acceleration |                         
  | TimeDomain-BodyAccelerationMagnitude-std |  Standard Deviation Magnitude for Body Acceleration |                      
  | TimeDomain-GravityAccelerationMagnitude-mean |       Mean Magnitude for Gravity Acceleration |                
  | TimeDomain-GravityAccelerationMagnitude-std |     Standard Deviation Magnitude for Gravity Acceleration |                   
  | TimeDomain-BodyAccelerationJerkMagnitude-mean |                      
  | TimeDomain-BodyAccelerationJerkMagnitude-std |                       
  | TimeDomain-BodyAngularVelocityMagnitude-mean |                       
  | TimeDomain-BodyAngularVelocityMagnitude-std |                        
  | TimeDomain-BodyAngularVelocityJerkMagnitude-mean |                   
  | TimeDomain-BodyAngularVelocityJerkMagnitude-std |                    
  | FrequencyDomain-BodyAcceleration-mean-X |                            
  | FrequencyDomain-BodyAcceleration-mean-Y |     Same for axis Y |                        
  | FrequencyDomain-BodyAcceleration-mean-Z |     Same for axis Z |                         
  | FrequencyDomain-BodyAcceleration-std-X |                             
  | FrequencyDomain-BodyAcceleration-std-Y |    Same for axis Y |                          
  | FrequencyDomain-BodyAcceleration-std-Z |      Same for axis Z |                         
  | FrequencyDomain-BodyAcceleration-meanFrequency-X |                   
  | FrequencyDomain-BodyAcceleration-meanFrequency-Y |   Same for axis Y |                 
  | FrequencyDomain-BodyAcceleration-meanFrequency-Z |  Same for axis Z |                   
  | FrequencyDomain-BodyAccelerationJerk-mean-X |                        
  | FrequencyDomain-BodyAccelerationJerk-mean-Y |   Same for axis Y |                      
  | FrequencyDomain-BodyAccelerationJerk-mean-Z |     Same for axis Z |                     
  | FrequencyDomain-BodyAccelerationJerk-std-X |                         
  | FrequencyDomain-BodyAccelerationJerk-std-Y |    Same for axis Y |                      
  | FrequencyDomain-BodyAccelerationJerk-std-Z |    Same for axis Z |                       
  | FrequencyDomain-BodyAccelerationJerk-meanFrequency-X |               
  | FrequencyDomain-BodyAccelerationJerk-meanFrequency-Y | Same for axis Y |               
  | FrequencyDomain-BodyAccelerationJerk-meanFrequency-Z |  Same for axis Z |               
  | FrequencyDomain-BodyAngularVelocity-mean-X |                         
  | FrequencyDomain-BodyAngularVelocity-mean-Y |    Same for axis Y |                      
  | FrequencyDomain-BodyAngularVelocity-mean-Z |    Same for axis Z |                       
  | FrequencyDomain-BodyAngularVelocity-std-X |                          
  | FrequencyDomain-BodyAngularVelocity-std-Y |   Same for axis Y |                        
  | FrequencyDomain-BodyAngularVelocity-std-Z |    Same for axis Z |                        
  | FrequencyDomain-BodyAngularVelocity-meanFrequency-X |                
  | FrequencyDomain-BodyAngularVelocity-meanFrequency-Y |   Same for axis Y |              
  | FrequencyDomain-BodyAngularVelocity-meanFrequency-Z |   Same for axis Z |               
  | FrequencyDomain-BodyAccelerationMagnitude-mean |                     
  | FrequencyDomain-BodyAccelerationMagnitude-std |                      
  | FrequencyDomain-BodyAccelerationMagnitude-meanFrequency |            
  | FrequencyDomain-BodyBodyAccelerationJerkMagnitude-mean |             
  | FrequencyDomain-BodyBodyAccelerationJerkMagnitude-std |              
  | FrequencyDomain-BodyBodyAccelerationJerkMagnitude-meanFrequency |    
  | FrequencyDomain-BodyBodyAngularVelocityMagnitude-mean |              
  | FrequencyDomain-BodyBodyAngularVelocityMagnitude-std |               
  | FrequencyDomain-BodyBodyAngularVelocityMagnitude-meanFrequency |     
  | FrequencyDomain-BodyBodyAngularVelocityJerkMagnitude-mean |          
  | FrequencyDomain-BodyBodyAngularVelocityJerkMagnitude-std |           
  | FrequencyDomain-BodyBodyAngularVelocityJerkMagnitude-meanFrequency | 
  | Subject |                                                            
  | Activity |                                     