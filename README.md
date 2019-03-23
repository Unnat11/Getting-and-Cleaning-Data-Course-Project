# Getting-and-Cleaning-Data-Course-Project
This repo was created to finish the assignment for week 4 of Getting and Cleaning Data Coursera course.

Description of the data used
The variables in the data X are sensor signals measured with waist-mounted smartphone from 30 subjects. The variable in the data Y indicates activity type the subjects performed during recording.

Explanation of the code
The code combined training dataset and test dataset, and extracted partial variables to create another dataset with the averages of each variable for each activity.

Tidy dataset created
The new generated dataset contained variables calculated based on the mean and standard deviation. Each row of the dataset is an average of each activity type for all subjects.

The code was written based on the following instructions of this assignment

You should create one R script called run_analysis.R that does the following.

Merges the training and the test sets to create one data set.
Extracts only the measurements on the mean and standard deviation for each measurement.
Uses descriptive activity names to name the activities in the data set
Appropriately labels the data set with descriptive variable names.
From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
