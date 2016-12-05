# getting-and-cleaning-data-project


This repository hosts the R code and documentation files for the Data Science's track course "Getting and Cleaning data",

The dataset being used is: [Human Activity Recognition Using Smartphones](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)
The source data for this project can be found here.](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip)


The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. 
The goal is to prepare tidy data that can be used for later analysis

`CodeBook.md` describes the variables, the data, and any transformations or work that was performed to clean up the data.

I am going To create one R script called run_analysis.R that does the following.

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject

So first of all I have to get the data unzip the file and then Read data from the targeted files
2. Read data from the files into the variables

You can find additional information about the variables, data and transformations in the CodeBook.MD file.

