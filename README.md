# Getting and Cleaning Data Course Project


Create one R script called run_analysis.R which does the following:

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## Instructions

1. Download the data source and put into a folder called ```UCI HAR Dataset```.
2. Copy ```run_analysis.R``` in the parent folder of ```UCI HAR Dataset```
3. Set ```UCI HAR Dataset``` as your working directory.
3. Run ```source("run_analysis.R")```. A new file ```tiny_data.txt``` will be generated in the working directory.

## Dependencies

Dependencies are ```data.table``` and ```reshape2```. 
