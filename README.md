# Getting-and-Cleaning-Data-project



###Course Instructions

**You should create one R script called run_analysis.R that does the following.**

1. Merges the training and the test sets to create one data set.

2. Extracts only the measurements on the mean and standard deviation for each measurement.

3. Uses descriptive activity names to name the activities in the data set

4. Appropriately labels the data set with descriptive activity names.

5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.



###The following are steps to working on this course project:

1. Download the data source and put into a folder on your local drive. Unzipping will create a UCI HAR Dataset folder.

2. Put run_analysis.R in the parent folder of UCI HAR Dataset, set this as your working directory using the setwd() function in RStudio.

3. Run source("run_analysis.R"), to generate a new file tinydata.txt in your working directory.



###Dependencies

1. Running run_analysis.R file will help you to install the dependencies automatically. You need reshape2 and data.table.
