## Getting and Cleaning Data - Course Project

This repository hosts the R script (and other files) asked by the Course Project of the "Getting and Cleaning data" track, from the Data Science Course, available in Coursera.


# How it works
The file `run_analysis.R` is a R script witch have 5 steps:

* In step 1, it use `rbind()` function to merge the similar data (same number of columns and same entities).
* In step 2, it take those columns with the mean and standard deviation measures, and it give the correct names according with `features.txt`.
* In step 3, it take the activity names and IDs from `activity_labels.txt` and substitute the activity data with values 1 to 6.
* In step 4, it give better names to columns.
* In step 5, it generate a output file named `averages_data.txt` with the average measures for each subject and activity type.


# Codebook
* To store the data from files: `x_train`, `y_train`, `x_test`, `y_test` and `subject_train`;
* To store the merging of datasets: `x_data`, `y_data` and `subject_data`;
* To store the correct names: `features`;
* To store the comumn names: `mean_and_std_features`;
* To store the activity names: `activities`;
* To store the merging of `x_data`, `y_data` and `subject_data`: `all_data`;
* To store the averages for the txt files: `averages_data`.


#Outputs
The output file generated in the step 5 of the script is named `averages_data.txt`.
