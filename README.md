# Cleaning_data

This repo was set up for the final assignment in the Getting and Cleaning data Coursera course.

The goal of this assignment is to create a tidy dataset of the data provided. 
The dataset provided is from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip.
A full description of the dataset can found at http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

The code script I wrote is called run_analysis.R and is in this repo. 
The script does the following:
1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names. 
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

There is also a codebook included in this repo going through the variables I used and the steps I took to trasnform the initial data to the a tidy dataset. 
