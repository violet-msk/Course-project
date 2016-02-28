# Getting-and-Cleaning-Data-Course-Project
Getting and Cleaning Data
Course Project

You should create one R script called run_analysis.R that does the following.

Merges the training and the test sets to create one data set.
Extracts only the measurements on the mean and standard deviation for each measurement.
Uses descriptive activity names to name the activities in the data set
Appropriately labels the data set with descriptive activity names.
Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

Steps:

1. Download raw data from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip and put into your working directory, extract the folder from zip file (the name should be the same with the initial one).
2. Run run_analysis.R, previously put it to the same folder with raw data. 
3. It will create a new file tiny_data.txt in your working directory.

Dependencies
run_analysis.R as the first steps install dependencies automatically (reshape2 and data.tab)
