Getting-and-Cleaning-Data
=========================
This is the submission of the course project for the Johns Hopkins "Getting and Cleaning Data" course.

## Files in this repo
* README.md -- general information about this repo
* CodeBook.md -- codebook describing variables, the data and transformations
* run_analysis.R -- actual R code

### Overview
This project serves to demonstrate the collection and cleaning of a tidy data set that can be used for subsequent
analysis. 

### Project Summary
The following is a summary description of the project instructions

You should create one R script called run_analysis.R that does the following. 
1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names. 
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 

### Steps to work on this course project

1. Download the data source and put into a folder on your c:\temp folder and unzip the file to "c:\temp\UCI HAR Dataset" folder.
2. The R code will set working directory to this data set folder.  You can also update the R code to the desired folder with the data set.
3. Run "source("run_analysis.R")", then it will generate a new file "tidydata.txt" in your working directory.

### Additional Information
You can find additional information about the variables, data and transformations in the CodeBook.MD file.

