# Getting and Cleaning Data Course Project
## CodeBook from Human Activity Recognition Using Smartphones Dataset

Original Data source : https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. 
A full description is available at the site where the data was obtained:
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

**Subject**
identifies the subject who performed the activity for each window sample. Its range is from 1 to 30. 
| Subject | id |
|------------|----|
| Subbjet 1 | 1 |
| Subject 2 | 2 |
| Subject 3 | 3 |
| Subject ... | ... |
| Subject 29 | 29 |
| Subject 30 | 30 |

**Activity**
identifies the activity type. 6 possibles value
 1. WALKING
 1. WALKING_UPSTAIRS
 1. WALKING_DOWNSTAIRS
 1. SITTING
 1. STANDING
 1. LAYING

**33 Mean values (mean())and 33 Standard deviations (std())** coming from the Samsung Galaxy S II subjets embedded accelerometer and gyroscope, that give the 3-axial linear acceleration and 3-axial angular velocity accelerometer and gyroscope 3-axial raw signals tAcc-XYZ and tGyro-XYZ. These time domain signals (prefix 't' to denote time) were captured at a constant rate of 50 Hz. The acceleration signal was then separated into body and gravity acceleration signals (tBodyAcc-XYZ and tGravityAcc-XYZ). The body linear acceleration and angular velocity were derived in time to obtain Jerk signals (tBodyAccJerk-XYZ and tBodyGyroJerk-XYZ). Also the magnitude of these three-dimensional signals were calculated using the Euclidean norm (tBodyAccMag, tGravityAccMag, tBodyAccJerkMag, tBodyGyroMag, tBodyGyroJerkMag). A Fast Fourier Transform (FFT) was applied to some of these signals producing fBodyAcc-XYZ, fBodyAccJerk-XYZ, fBodyGyro-XYZ, fBodyAccJerkMag, fBodyGyroMag, fBodyGyroJerkMag. (Note the 'f' to indicate frequency domain signals). 

 1. tBodyAcc-mean()-Z 
 1. tBodyAcc-std()-X 
 1. tBodyAcc-std()-Y 
 1. tGravityAcc-mean()-Z 
 1. tGravityAcc-std()-X 
 1. tGravityAcc-std()-Y 
 1. tBodyAccJerk-mean()-Z 
 1. tBodyAccJerk-std()-X 
 1. tBodyAccJerk-std()-Y 
 1. tBodyGyro-mean()-Z 
 1. tBodyGyro-std()-X 
 1. tBodyGyro-std()-Y 
 1. tBodyGyroJerk-mean()-Z 
 1. tBodyGyroJerk-std()-X 
 1. tBodyGyroJerk-std()-Y 
 1. tBodyAccMag-mad() 
 1. tGravityAccMag-mad() 
 1. tBodyAccJerkMag-mad() 
 1. tBodyGyroMag-mad() 
 1. tBodyGyroJerkMag-mad() 
 1. fBodyAcc-mean()-Z 
 1. fBodyAcc-std()-X 
 1. fBodyAcc-std()-Y 
 1. fBodyAccJerk-mean()-Z 
 1. fBodyAccJerk-std()-X 
 1. fBodyAccJerk-std()-Y 
 1. fBodyGyro-mean()-Z 
 1. fBodyGyro-std()-X 
 1. fBodyGyro-std()-Y 
 1. fBodyAccMag-mad() 
 1. fBodyBodyAccJerkMag-mad() 
 1. fBodyBodyGyroMag-mad() 
 1. fBodyBodyGyroJerkMag-mad() 
 1. tBodyAcc-mean()-Z 
 1. tBodyAcc-std()-X 
 1. tBodyAcc-std()-Y 
 1. tGravityAcc-mean()-Z 
 1. tGravityAcc-std()-X 
 1. tGravityAcc-std()-Y 
 1. tBodyAccJerk-mean()-Z 
 1. tBodyAccJerk-std()-X 
 1. tBodyAccJerk-std()-Y 
 1. tBodyGyro-mean()-Z 
 1. tBodyGyro-std()-X 
 1. tBodyGyro-std()-Y 
 1. tBodyGyroJerk-mean()-Z 
 1. tBodyGyroJerk-std()-X 
 1. tBodyGyroJerk-std()-Y 
 1. tBodyAccMag-mad() 
 1. tGravityAccMag-mad() 
 1. tBodyAccJerkMag-mad() 
 1. tBodyGyroMag-mad() 
 1. tBodyGyroJerkMag-mad() 
 1. fBodyAcc-mean()-Z 
 1. fBodyAcc-std()-X 
 1. fBodyAcc-std()-Y 
 1. fBodyAccJerk-mean()-Z 
 1. fBodyAccJerk-std()-X 
 1. fBodyAccJerk-std()-Y 
 1. fBodyGyro-mean()-Z 
 1. fBodyGyro-std()-X 
 1. fBodyGyro-std()-Y 
 1. fBodyAccMag-mad() 
 1. fBodyBodyAccJerkMag-mad() 
 1. fBodyBodyGyroMag-mad() 
 1. fBodyBodyGyroJerkMag-mad()
