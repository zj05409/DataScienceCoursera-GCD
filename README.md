# DataScienceCoursera-GCD
==================================================================
Getting and Cleaning Data Course Project
Version 1.0
==================================================================
John Jay
zj05409@qq.com
==================================================================

The background

This project is my answer to the course project at  https://www.coursera.org/learn/data-cleaning/peer/FIZtT/getting-and-cleaning-data-course-project

The dataset includes the following files:
=========================================

- 'README.txt'

- 'run_analysis.R': a script which merges and cleans the original data sets.

The script do the following: 
=========================================
- merges the test, training, subjects and activities data sets from [1] http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 
- extract the mean and std columns, 
- modifies the names of the columns, 
- change the activity column from number to the corresponding labels.

After running this script, you will get a file named "ucihardata.txt", which contain a tidy data set.

The resulting dataset contains the following colomns:
======================================

- "subject" is the person id
- "activity" is the type of the actions taken by the person, with the following values: WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING
- "tBodyAccMean-X","tBodyAccMean-Y","tBodyAccMean-Z" Mean value of triaxial body acceleration raw data
- "tBodyAccStd-X","tBodyAccStd-Y","tBodyAccStd-Z" Standard deviation value of triaxial body acceleration raw data
- "tGravityAccMean-X","tGravityAccMean-Y","tGravityAccMean-Z" Mean value of triaxial gravity acceleration raw data
- "tGravityAccStd-X","tGravityAccStd-Y","tGravityAccStd-Z" Standard deviation value of triaxial gravity acceleration raw data
- "tBodyAccJerkMean-X","tBodyAccJerkMean-Y","tBodyAccJerkMean-Z" Mean value of triaxial body linear acceleration
- "tBodyAccJerkStd-X","tBodyAccJerkStd-Y","tBodyAccJerkStd-Z" Standard deviation value of triaxial body linear acceleration
- "tBodyGyroMean-X","tBodyGyroMean-Y","tBodyGyroMean-Z" Mean value of triaxial body angular velocity raw data
- "tBodyGyroStd-X","tBodyGyroStd-Y","tBodyGyroStd-Z" Standard deviation value of triaxial body angular velocity raw data
- "tBodyGyroJerkMean-X","tBodyGyroJerkMean-Y","tBodyGyroJerkMean-Z" Mean value of triaxial body linear angular velocity
- "tBodyGyroJerkStd-X","tBodyGyroJerkStd-Y","tBodyGyroJerkStd-Z" Standard deviation value of triaxial body linear angular velocity
- "tBodyAccMagMean" Mean value of body acceleration raw data magnitude
- "tBodyAccMagStd" Standard deviation value of body acceleration raw data magnitude
- "tGravityAccMagMean" Mean value of gravity acceleration raw data magnitude
- "tGravityAccMagStd" Standard deviation of gravity acceleration raw data magnitude
- "tBodyAccJerkMagMean" Mean value of body linear acceleration magnitude
- "tBodyAccJerkMagStd" Standard deviation value of body linear acceleration magnitude
- "tBodyGyroMagMean" Mean value of body angular velocity raw data magnitude
- "tBodyGyroMagStd" Standard deviation value of body angular velocity raw data magnitude
- "tBodyGyroJerkMagMean" Mean value of body linear angular velocity magnitude
- "tBodyGyroJerkMagStd" Standard deviation value of body linear angular velocity magnitude
- "fBodyAccMean-X","fBodyAccMean-Y","fBodyAccMean-Z" FFT of "tBodyAccMean-X","tBodyAccMean-Y","tBodyAccMean-Z"
- "fBodyAccStd-X","fBodyAccStd-Y","fBodyAccStd-Z" FFT of 
- "fBodyAccJerkMean-X","fBodyAccJerkMean-Y","fBodyAccJerkMean-Z" FFT of "tBodyAccJerkMean-X","tBodyAccJerkMean-Y","tBodyAccJerkMean-Z"
- "fBodyAccJerkStd-X","fBodyAccJerkStd-Y","fBodyAccJerkStd-Z" FFT of "tBodyAccJerkStd-X","tBodyAccJerkStd-Y","tBodyAccJerkStd-Z"
- "fBodyGyroMean-X","fBodyGyroMean-Y","fBodyGyroMean-Z" FFT of "tBodyGyroMean-X","tBodyGyroMean-Y","tBodyGyroMean-Z"
- "fBodyGyroStd-X","fBodyGyroStd-Y","fBodyGyroStd-Z" FFT of "tBodyGyroStd-X","tBodyGyroStd-Y","tBodyGyroStd-Z"
- "fBodyAccMagMean" FFT of "tBodyAccMagMean"
- "fBodyAccMagStd" FFT of "tBodyAccMagStd"
- "fBodyBodyAccJerkMagMean" FFT of "tBodyBodyAccJerkMagMean"
- "fBodyBodyAccJerkMagStd" FFT of "tBodyBodyAccJerkMagStd" 
- "fBodyBodyGyroMagMean" FFT of "tBodyBodyGyroMagMean" 
- "fBodyBodyGyroMagStd" FFT of "tBodyBodyGyroMagStd" 
- "fBodyBodyGyroJerkMagMean" FFT of "tBodyBodyGyroJerkMagMean" 
- "fBodyBodyGyroJerkMagStd" FFT of "tBodyBodyGyroJerkMagStd" 

Notes: 
======
- To run the script, you should first download the dataset from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip and unzip it in the same folder as the script.

References:
========
[1] Davide Anguita, Alessandro Ghio, Luca Oneto, Xavier Parra and Jorge L. Reyes-Ortiz. Human Activity Recognition on Smartphones using a Multiclass Hardware-Friendly Support Vector Machine. International Workshop of Ambient Assisted Living (IWAAL 2012). Vitoria-Gasteiz, Spain. Dec 2012

John Jay. September 2016.
