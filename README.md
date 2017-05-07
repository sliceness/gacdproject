# Class Project for "Getting and Cleaning Data"

You should create one R script called run_analysis.R that does the following.

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names.
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## Steps to work on this course project

1. Download the data as a zip file from [this URL](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip).
2. Unzip the files, which should have all the data in the UCI HAR Dataset folder.
3. Downlad run_analysis.R in the parent folder of UCI HAR Dataset.
4. Run run_analysis.R, and it will generate a new file ```tidydataset.txt``` in your working directory. It requires the reshape2 package.

You can read more about the data and the analysis in the code book.
