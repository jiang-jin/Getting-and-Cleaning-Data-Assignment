# JHP03_Assignment
# Getting and Cleaning Data - Assignment
Course Project

1. Assignment <br />
Create one R script called run_analysis.R in Github that does the following. <br />

2. Requirement   <br />
2.1 Merges the training and the test sets to create one data set. <br />
2.2 Extracts only the measurements on the mean and standard deviation for each measurement. <br />
2.3 Uses descriptive activity names to name the activities in the data set. <br />
2.4 Appropriately labels the data set with descriptive activity names. <br />
2.5 Creates a second, independent tidy data set with the average of each variable for each activity and each subject.<br />

3. Steps to work on this course project <br />
3.1 Download the data source and put into a folder on your local drive. You'll have a UCI HAR Dataset folder. For Mac user, you can use "~/Desktop/WorkDirectory/UCI HAR Dataset" as route. <br />
3.2 Put run_analysis.R in the parent folder of UCI HAR Dataset, then set it as your working directory using setwd() function in RStudio.  <br />
3.3 Run source("run_analysis.R"), then it will generate a new file tiny_data.txt in your working directory.  <br />

Note: <br />
run_analysis.R file will help you to install the dependencies automatically. It depends on reshape2 and data.table.

