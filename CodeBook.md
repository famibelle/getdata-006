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
| Subjet 1 | 1 |
| Subject 2 | 2 |
| Subject 3 | 3 |
| Subject ... | ... |
| Subject 29 | 29 |
| Subject 30 | 30 |

**Activity**
identifies the activity type. 6 possibles value
```
 1. WALKING
 2. WALKING_UPSTAIRS
 3. WALKING_DOWNSTAIRS
 4. SITTING
 5. STANDING
 6. LAYING
```

**66 variables : 33 Mean values (mean())and 33 Standard deviations (std())** coming from the Samsung Galaxy S II subjets embedded accelerometer and gyroscope, that give the 3-axial linear acceleration and 3-axial angular velocity accelerometer and gyroscope 3-axial raw signals tAcc-XYZ and tGyro-XYZ. These time domain signals (prefix 't' to denote time) were captured at a constant rate of 50 Hz. The acceleration signal was then separated into body and gravity acceleration signals (tBodyAcc-XYZ and tGravityAcc-XYZ). The body linear acceleration and angular velocity were derived in time to obtain Jerk signals (tBodyAccJerk-XYZ and tBodyGyroJerk-XYZ). Also the magnitude of these three-dimensional signals were calculated using the Euclidean norm (tBodyAccMag, tGravityAccMag, tBodyAccJerkMag, tBodyGyroMag, tBodyGyroJerkMag). A Fast Fourier Transform (FFT) was applied to some of these signals producing fBodyAcc-XYZ, fBodyAccJerk-XYZ, fBodyGyro-XYZ, fBodyAccJerkMag, fBodyGyroMag, fBodyGyroJerkMag. (Note the 'f' to indicate frequency domain signals). 
```
 1. tBodyAcc-mean()-Z 
 2. tBodyAcc-std()-X 
 3. tBodyAcc-std()-Y 
 4. tGravityAcc-mean()-Z 
 5. tGravityAcc-std()-X 
 6. tGravityAcc-std()-Y 
 7. tBodyAccJerk-mean()-Z 
 8. tBodyAccJerk-std()-X 
 9. tBodyAccJerk-std()-Y 
 10. tBodyGyro-mean()-Z 
 11. tBodyGyro-std()-X 
 12. tBodyGyro-std()-Y 
 13. tBodyGyroJerk-mean()-Z 
 14. tBodyGyroJerk-std()-X 
 15. tBodyGyroJerk-std()-Y 
 16. tBodyAccMag-mad() 
 17. tGravityAccMag-mad() 
 18. tBodyAccJerkMag-mad() 
 19. tBodyGyroMag-mad() 
 20. tBodyGyroJerkMag-mad() 
 21. fBodyAcc-mean()-Z 
 22. fBodyAcc-std()-X 
 23. fBodyAcc-std()-Y 
 24. fBodyAccJerk-mean()-Z 
 25. fBodyAccJerk-std()-X 
 26. fBodyAccJerk-std()-Y 
 27. fBodyGyro-std()-X 
 28. fBodyGyro-std()-Y 
 29. fBodyAccMag-mad() 
 30. fBodyBodyAccJerkMag-mad() 
 31. fBodyBodyGyroMag-mad() 
 32. fBodyBodyGyroJerkMag-mad() 
 33. tBodyAcc-mean()-Z 
 34. tBodyAcc-std()-X 
 35. tBodyAcc-std()-Y 
 36. tGravityAcc-mean()-Z 
 37. tGravityAcc-std()-X 
 38. tGravityAcc-std()-Y 
 39. tBodyAccJerk-mean()-Z 
 40. tBodyAccJerk-std()-X 
 41. tBodyAccJerk-std()-Y 
 42. tBodyGyro-mean()-Z 
 43. tBodyGyro-std()-X 
 44. tBodyGyro-std()-Y 
 45. tBodyGyroJerk-mean()-Z 
 46. tBodyGyroJerk-std()-X 
 47. tBodyGyroJerk-std()-Y 
 48. tBodyAccMag-mad() 
 49. tGravityAccMag-mad() 
 50. tBodyAccJerkMag-mad() 
 51. tBodyGyroMag-mad() 
 52. tBodyGyroJerkMag-mad() 
 53. fBodyAcc-mean()-Z 
 54. fBodyAcc-std()-X 
 55. fBodyAcc-std()-Y 
 56. fBodyAccJerk-mean()-Z 
 57. fBodyAccJerk-std()-X 
 58. fBodyAccJerk-std()-Y 
 59. fBodyGyro-mean()-Z 
 60. fBodyGyro-std()-X 
 61. fBodyGyro-std()-Y 
 62. fBodyAccMag-mad() 
 63. fBodyBodyAccJerkMag-mad() 
 64. fBodyBodyGyroMag-mad() 
 65. fBodyBodyGyroJerkMag-mad()
 66. fBodyGyro-mean()-Z
```
