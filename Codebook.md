---
title: "Codebook"
author: "David"
date: "5/26/2021"
output: html_document
---
Codebook going through the variables and and steps for the data cleaning project

#Source Files
train_data: Training data set observations 
test_data: Test data set observations
train_labels: Training data set labels
test_labels: Test data set labels
train_subjects: Training data set subjects
test_subjects: Test data set subjects
features_file: Feature names
activity_labels_file: Mapping of activity labels to text labels

#Varibales created
total_data: Combined data set of training and test observations
total_labels: Combined data set of training and test labels
total_subjects: Combined data set of training and test subjects
col_nums: The column numbers from the feature list of the features that contain
either "mean" or "std" in their title
col_name: The column names from the feature list of the features that contain
either "mean" or "std" in their title
complete_data: Combined data set of all the subjects, activty labels, and observations
avg_dataset: Data set showing the average value for all features grouped by the subject
and the activity

#Transformations
1.Original total_data data set columns are selected from to only include columns 
identified as containing "mean" or "std" in their title
2. total_labels is transformed to text labels via matching to the activity_labels_file
3. The column names of the complete_data data set are changed to the names "subject",
"activity_label", and the names of the features from the features file
4. Averages for avg_dataset computed using the summarize command from dplyr



