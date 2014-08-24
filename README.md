getdata-006
===========

# Getting and Cleaning Data Course Project
Describing how the script works

the run_analysis.R script runs as follow to clean the data and create the tidy data.
### 1/ Merges the training and the test sets to create one data set.
+ Read "features.txt", "activity_labels.txt" from directory "UCIHARDataset/" and store them in dataframes named respectively Features, Activity_labels 
+ Read "y_train.txt", "X_train.txt", "subject_train.txt" from directory "UCIHARDataset/train" and store them in dataframes names respectively Train_y_text, Train_X_text, Train_Subject
+ Read "y_test.txt", "X_test.txt", "subject_test.txt" from directory "UCIHARDataset/test" and store them in dataframes names respectively Test_y_text, Train_X_text, Train_Subject
+ Merge with `cbind()` the Train_Subject, Train_y_text, Train_X_text  into a TrainData dataframe
+ Merge with `cbind()` the Test_Subject, Test_y_text, Test_X_text  into a TestData dataframe
+ Merge with `rbind()` the TestData and the TrainData into a MergedData dataframe of 563 columns and 10299 rows.

### 2/ Extracts only the measurements on the mean and standard deviation for each measurement.  
+ Extract column indices with character string containing "mean()" and offset by 2 to match the subjet and activity names
+ Extract column indices with character string == "std()" and  offset by 2 to match the subjet and activity names
+ Merge with `cbind()` into a MergedData_MeanSTD dataframe
	
### 	3/ Uses descriptive activity names to name the activities in the data set
+ with the help of Activity_labels

### 4/ Label the data set with descriptive variable names. 
+ with the help of a MergedData_ColNames vector containing all the column names 
+ not requested in the project, but still usefull create a "MergedData_MeanSTD.txt" text file with all the data

### 	5/ Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 
+ return the result and write to a file to "tidydataset.txt" file in current working directory.
+ that's it
