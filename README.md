# Getting and Cleaning Data - Course Project

Download the dataset if it does not already exist in the working directory

Load the activity and feature info

Loads both the training and test datasets, keeping only those columns which reflect a mean or standard deviation

Loads the activity and subject data for each dataset, and merges those columns with the dataset

Merges the two datasets

Converts the activity and subject columns into factors

Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.

The end result is shown in the file tidy.txt.
## Files

The code takes for granted all the data is present in the same folder, un-compressed and without names altered.

CodeBook.md describes the variables, the data, and any transformations or work that was performed to clean up the data.

run_analysis.R contains all the code to perform the analyses described in the 5 steps. They can be launched in RStudio by just importing the file.

The output of the 5th step is called averages_data.txt, and uploaded in the course project's form.
