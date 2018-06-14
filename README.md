# TidyData

This is the assignment for the Getting and Cleaning Data course. The R script, run_analysis.R, does the following:

Download the dataset if it does not already exist in the working directory <br/>
Load the activity and feature info <br/>
Loads both the training and test datasets, keeping only those columns which reflect a mean or standard deviation <br/>
Loads the activity and subject data for each dataset, and merges those columns with the dataset <br/>
Merges the two datasets <br/>
Converts the activity and subject columns into factors <br/>
Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.

The end result is shown in the file tidydata.txt.
