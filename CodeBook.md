---
title: Codebook for Human_Activity_Recognition_Dataset
subtitle: "Course"
date: 2019-01-14
---

# Data Overview
The dataset examined has the following dimensions:


| Feature                  | Result|
|-------------------------:|------:|
| Number of observations   |  40   |
| Number of variables      |  82   |


# Data Summary
    
| Type                                        |    Variables                                              | Class     |Unique|
|---------------------------------------------------------------------------------------------------------|:---------:|-----:|
| Activity                                    | ActivityId                                                |  integer  |    6 |
| Activity                                    | Activity                                                  | character |    6 | 
| Subject                                     | Subject                                                   |  integer  |   30 | 
| Time Domain                                 | timeBodyAccelerometerMean.Y                               |  integer  |   40 |
| Time Domain                                 | timeBodyAccelerometerMean.Z                               |  integer  |   40 |
| Time Domain                                 | timeGravityAccelerometerMean.X                            |  integer  |   40 |
| Time Domain                                 | timeGravityAccelerometerMean.Y                            |  integer  |   40 |
| Time Domain                                 | timeGravityAccelerometerMean.Z                            |  integer  |   40 |
| Time Domain                                 | timeBodyAccelerometerJerkMean.X                           |  integer  |   40 |
| Time Domain                                 | timeBodyAccelerometerJerkMean.Y                           |  integer  |   40 |
| Time Domain                                 | timeBodyAccelerometerJerkMean.Z                           |  integer  |   40 |
| Time Domain                                 | timeBodyGyroscopeMean.X                                   |  integer  |   40 |
| Time Domain                                 | timeBodyGyroscopeMean.Y                                   |  integer  |   40 |
| Time Domain                                 | timeBodyGyroscopeMean.Z                                   |  integer  |   40 |
| Time Domain                                 | timeBodyGyroscopeJerkMean.X                               |  integer  |   40 |
| Time Domain                                 | timeBodyGyroscopeJerkMean.Y                               |  integer  |   40 |
| Time Domain                                 | timeBodyGyroscopeJerkMean.Z                               |  integer  |   40 |
| Time Domain                                 | timeBodyAccelerometerMagnitudeMean                        |  integer  |   40 |
| Time Domain                                 | timeGravityAccelerometerMagnitudeMean                     |  integer  |   40 |
| Time Domain                                 | timeBodyAccelerometerJerkMagnitudeMean                    |  integer  |   40 |
| Time Domain                                 | timeBodyGyroscopeMagnitudeMean                            |  integer  |   40 |
| Time Domain                                 | timeBodyGyroscopeJerkMagnitudeMean                        |  integer  |   40 |
| Frequency Domain                            | frequencyBodyAccelerometerMean.X                          |  integer  |   40 |
| Frequency Domain                            | frequencyBodyAccelerometerMean.Y                          |  integer  |   40 |
| Frequency Domain                            | frequencyBodyAccelerometerMean.Z                          |  integer  |   40 |
| Frequency Domain                            | frequencyBodyAccelerometerMeanFrequency.X                 |  integer  |   40 |
| Frequency Domain                            | frequencyBodyAccelerometerMeanFrequency.Y                 |  integer  |   40 |
| Frequency Domain                            | frequencyBodyAccelerometerMeanFrequency.Z                 |  integer  |   40 |
| Frequency Domain                            | frequencyBodyAccelerometerJerkMean.X                      |  integer  |   40 |
| Frequency Domain                            | frequencyBodyAccelerometerJerkMean.Y                      |  integer  |   40 |
| Frequency Domain                            | frequencyBodyAccelerometerJerkMean.Z                      |  integer  |   40 |
| Frequency Domain                            | frequencyBodyAccelerometerJerkMeanFrequency.X             |  integer  |   40 |
| Frequency Domain                            | frequencyBodyAccelerometerJerkMeanFrequency.Y             |  integer  |   40 |
| Frequency Domain                            | frequencyBodyAccelerometerJerkMeanFrequency.Z             |  integer  |   40 |
| Frequency Domain                            | frequencyBodyGyroscopeMean.X                              |  integer  |   40 |
| Frequency Domain                            | frequencyBodyGyroscopeMean.Y                              |  integer  |   40 |
| Frequency Domain                            | frequencyBodyGyroscopeMean.Z                              |  integer  |   40 |
| Frequency Domain                            | frequencyBodyGyroscopeMeanFrequency.X                     |  integer  |   40 |
| Frequency Domain                            | frequencyBodyGyroscopeMeanFrequency.Y                     |  integer  |   40 |
| Frequency Domain                            | frequencyBodyGyroscopeMeanFrequency.Z                     |  integer  |   40 |
| Frequency Domain                            | frequencyBodyAccelerometerMagnitudeMean                   |  integer  |   40 |
| Frequency Domain                            | frequencyBodyAccelerometerMagnitudeMeanFrequency          |  integer  |   40 |
| Frequency Domain                            | frequencyBodyBodyAccelerometerJerkMagnitudeMean           |  integer  |   40 |
| Frequency Domain                            | frequencyBodyBodyAccelerometerJerkMagnitudeMeanFrequency  |  integer  |   40 |
| Frequency Domain                            | frequencyBodyBodyGyroscopeMagnitudeMean                   |  integer  |   40 |
| Frequency Domain                            | frequencyBodyBodyGyroscopeMagnitudeMeanFrequency          |  integer  |   40 |
| Frequency Domain                            | frequencyBodyBodyGyroscopeJerkMagnitudeMean               |  integer  |   40 |
| Frequency Domain                            | frequencyBodyBodyGyroscopeJerkMagnitudeMeanFrequency      |  integer  |   40 |
| Body Acceleration                           | angletBodyAccelerometerMeanGravity                        |  integer  |   40 |
| Body Acceleration                           | angletBodyAccelerometerJerkMeanGravityMean                |  integer  |   40 |
| Time Domain                                 | timeBodyAccelerometerStd.X                                |  integer  |   40 |
| Time Domain                                 | timeBodyAccelerometerStd.Y                                |  integer  |   40 |
| Time Domain                                 | timeBodyAccelerometerStd.Z                                |  integer  |   40 |
| Time Domain                                 | timeGravityAccelerometerStd.X                             |  integer  |   40 |
| Time Domain                                 | timeGravityAccelerometerStd.Y                             |  integer  |   40 |
| Time Domain                                 | timeGravityAccelerometerStd.Z                             |  integer  |   40 |
| Time Domain                                 | timeBodyAccelerometerJerkStd.X                            |  integer  |   40 |
| Time Domain                                 | timeBodyAccelerometerJerkStd.Y                            |  integer  |   40 |
| Time Domain                                 | timeBodyAccelerometerJerkStd.Z                            |  integer  |   40 |
| Time Domain                                 | timeBodyGyroscopeStd.X                                    |  integer  |   40 |
| Time Domain                                 | timeBodyGyroscopeStd.Y                                    |  integer  |   40 |
| Time Domain                                 | timeBodyGyroscopeStd.Z                                    |  integer  |   40 |
| Time Domain                                 | timeBodyGyroscopeJerkStd.X                                |  integer  |   40 |
| Time Domain                                 | timeBodyGyroscopeJerkStd.Y                                |  integer  |   40 |
| Time Domain                                 | timeBodyGyroscopeJerkStd.Z                                |  integer  |   40 |
| Time Domain                                 | timeBodyAccelerometerMagnitudeStd                         |  integer  |   40 |
| Time Domain                                 | timeGravityAccelerometerMagnitudeStd                      |  integer  |   40 |
| Time Domain                                 | timeBodyAccelerometerJerkMagnitudeStd                     |  integer  |   40 |
| Time Domain                                 | timeBodyGyroscopeMagnitudeStd                             |  integer  |   40 |
| Time Domain                                 | timeBodyGyroscopeJerkMagnitudeStd                         |  integer  |   40 |
| Frequency Domain                            | frequencyBodyAccelerometerStd.X                           |  integer  |   40 |
| Frequency Domain                            | frequencyBodyAccelerometerStd.Y                           |  integer  |   40 |
| Frequency Domain                            | frequencyBodyAccelerometerStd.Z                           |  integer  |   40 |
| Frequency Domain                            | frequencyBodyAccelerometerJerkStd.X                       |  integer  |   40 |
| Frequency Domain                            | frequencyBodyAccelerometerJerkStd.Y                       |  integer  |   40 |
| Frequency Domain                            | frequencyBodyAccelerometerJerkStd.Z                       |  integer  |   40 |
| Frequency Domain                            | frequencyBodyGyroscopeStd.X                               |  integer  |   40 |
| Frequency Domain                            | frequencyBodyGyroscopeStd.Y                               |  integer  |   40 |
| Frequency Domain                            | frequencyBodyGyroscopeStd.Z                               |  integer  |   40 |
| Frequency Domain                            | frequencyBodyAccelerometerMagnitudeStd                    |  integer  |   40 |
| Frequency Domain                            | frequencyBodyBodyAccelerometerJerkMagnitudeStd            |  integer  |   40 |
| Frequency Domain                            | frequencyBodyBodyGyroscopeMagnitudeStd                    |  integer  |   40 |
| Frequency Domain                            | frequencyBodyBodyGyroscopeJerkMagnitudeStd                |  integer  |   40 |

# Processing Steps

## Data Source : 
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

## Processing Script run_analysis.R that does the following.

-Loads training, test, features, subject and activity data

-Merge training and the test sets to create one data set.

-Extracts only the measurements on the mean and standard deviation for each measurement.

-Appropriately label the data set with descriptive variable names.

-Creates independent tidy data set with the average of each variable for each activity and each subject.