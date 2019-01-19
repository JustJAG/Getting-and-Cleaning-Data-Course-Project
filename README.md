# Getting-and-Cleaning-Data-Course-Project
Getting and Cleaning Data: Human Activity Recognition Using Smartphones Data Set 

#
# run_analysis.R
Companies like Fitbit, Nike, and Jawbone Up are racing to develop the most#  advanced algorithms to attract new users. The data used represents data
collected from the accelerometers # from the Samsung Galaxy S smartphone.

#  A full description is available at the site where the data was obtained:

#  Additional Info :
  http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

#  Data:
   https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

#  Processing:

 (1) Merges the training and the test sets to create one data set.
 (2) Extracts only the measurements on the mean and standard deviation for each measurement.
 (3) Uses descriptive activity names to name the activities in the data set
 (4) Appropriately labels the data set with descriptive variable names.
 (5) From the data set in step 4, creates a second, independent tidy data set
     with the average of each variable for each activity and each subject.

#  How to Run: run_analysis <- function() { ... } at R console

(1) Load  source("run_analysis.R")

(2) tidy_data <- run_analysis() 
      (returns tidy dataframe and writes output to txt file : tidy_data.txt)
      
# Log Output run_analysis.R     

 > tidy_data <- run_analysis()
[1] "extracting only the measurements on the mean and standard deviation"
[1] "STEP1: Loading Training and Test Datasets"
[1] "downloading :  UCI HAR Dataset.zip"
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100 59.6M  100 59.6M    0     0  46432      0  0:22:27  0:22:27 --:--:--  129k

[1] "extracting only the measurements on the mean and standard deviation"
[1] "Step1: Loading Training and Test Datasets"
[1] "Loading from:  UCI HAR Dataset/train  :  3  data file(s)"
[1] "Loading from:  UCI HAR Dataset/test  :  3  data file(s)"
[1] "Loading from:  UCI HAR Dataset  :  4  data file(s)"
[1] "Step1: DONE"
[1] "STEP2 : BEGIN"
[1] "BEGIN: 2.1 Merge the training dataset"
Joining, by = "Activity_Id"
[1] "DONE: 2.1 Merge the training dataset"
[1] "BEGIN: 2.2 Merge the test dataset"
Joining, by = "Activity_Id"
[1] "DONE: 2.2 Merge the test dataset"
[1] "BEGIN: 2.3 Merge the training and the test sets to create one data set."
[1] "DONE: 2.3 Merge the training and the test sets to create one data set."
[1] "STEP2 : DONE"
[1] "grouping by Activity and Subject"
[1] "summarise_all(funs(mean))"
