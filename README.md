# Coursera Getting and Cleaning Data Course Project

# Info

The script run_analysis.R requires the dataset UCI HAR, which can be downloaded here: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

The user should also edit the script to set the working directory to the directory that has the UCI HAR Dataset folder.  This script also requires the R library "reshape2" to be installed.

This script will load the test and train set from the UCI HAR dataset, taking only the mean and standard deviation for both.  It will then merge both datasets together and label this new set accordingly.  It will also create a second, independent tidy data set with the average of each variable for each activity and subject.
