# Getting and Cleaning Data - Course Project

The R script, `run_analysis.R`, does the following:

1. Loads the activity and feature info.
2. Loads the training and test datasets. Only those columns which reflect a mean or standard deviation are kept.
3. Loads the activity and subject data for each dataset, and merge these columns with the dataset
4. Merges the two datasets
5. Converts the activity and subject columns into factors
6. Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.

The file `tidy.txt` contains the end result of the script.