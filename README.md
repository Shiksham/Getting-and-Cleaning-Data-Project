

# Getting and Cleaning Data

* Course Project

Create a R script named run_analysis.R which does the following.

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names.
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

# Steps to be followed for this course project

1. Download the data source into a folder on your local drive. You'll have a "UCI HAR Dataset" folder after unzip.
2. Put "run_analysis.R" in the parent folder of "UCI HAR Dataset"
3. Set it as your working directory using "setwd()" function in RStudio.
4. Then run "source("run_analysis.R")" excluding first and last inverted commas. This will then generate a new file "tidy_data.txt" in your working directory. 

# Dependencies

"run_analysis.R" file will help you to install the dependencies automatically. It depends on "reshape2" and "data.table". 

