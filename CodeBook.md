About source data
As sourse data for work was used Human Activity Recognition Using Smartphones Data Set. 
A full description is available at the site where the data was obtained: 
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 
Here are the data for the project: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

About R script
File with R code "run_analysis.R" perform 5 following steps (as in the assigned task of course work):

1.Merging the training and the test sets to create one data set.
A) Reading files
A1) Reading trainings tables
A2) Reading testing tables
A3) Reading feature vector
A4) Reading activity labels
B) Assigning column names
C) Merging all data in one set
2.Extracting only the measurements on the mean and standard deviation for each measurement
A) Reading column names
B) Create vector for defining ID, mean and standard deviation
C) Making necessary subset from Merged
Using descriptive activity names to name the activities in the data set
Appropriately labeling the data set with descriptive variable names
5.Creating a second, independent tidy data set with the average of each variable for each activity and each subject
A) Making second tidy data set
B) Writing second tidy data set in txt file
PS..The code takes for granted all the data is present in the same folder, un-compressed and without names altered.

About variables:
x_train, y_train, x_test, y_test, subject_train and subject_test contain the data from the downloaded files.
x_data, y_data and subject_data merge the previous datasets to further analysis.
features contains the correct names for the x_data dataset, which are applied to the column names stored.
