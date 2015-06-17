# Getting_and_Cleaning_Data_Course-Project

##Creates one R script called run_analysis.R that does the following. 

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names. 
5. Creates a second independent tidy data set with the average of each variable for each activity and each subject.

##How to work on this project.

Download the data source and put into a folder on your local drive. You'll have a UCI HAR Dataset folder.
Put run_analysis.R in the parent folder of UCI HAR Dataset, then set it as your working directory using setwd() function in RStudio.
Run source("run_analysis.R"), then it will generate a new file tiny_data.txt in your working directory.

##R packages required.

run_analysis.R file will help you to install the dependencies automatically. It depends on reshape2 and data.table. 
