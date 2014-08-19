Getting and Cleaning Data Course Project CodeBook

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

the run_analysis.R script runs as follow to clean the data and create the tidy data.
+ Read "features.txt", "activity_labels.txt" from directory "UCIHARDataset/" and store them in dataframes named respectively Features, Activity_labels 
+ Read "y_train.txt", "X_train.txt", "subject_train.txt" from directory "UCIHARDataset/train" and store them in dataframes names respectively Train_y_text, Train_X_text, Train_Subject
+ Read "y_test.txt", "X_test.txt", "subject_test.txt" from directory "UCIHARDataset/test" and store them in dataframes names respectively Test_y_text, Train_X_text, Train_Subject
+ Merge with cbind the Train_Subject, Train_y_text, Train_X_text  into a TrainData dataframe
+ Merge with cbind the Test_Subject, Test_y_text, Test_X_text  into a TestData dataframe
+ Merge with rbind the TestData and the TrainData into a MergedData dataframe of 563 columns and 10299 rows.
