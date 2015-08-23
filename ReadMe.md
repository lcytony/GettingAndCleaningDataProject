# Getting and Cleaning Data

## Course Project

You should create one R script called run_analysis.R that does the following.

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names.
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## Steps to work on this course project

1. Set the working directory to the file ```UCI HAR Dataset```
2. Read all the related .txt file into R
3. Merge the train and together
4. Using information in ```features.txt``` to decide which variables are means and standard deviations
5. Select the related statistic feature from the data
6. Link the activity label with the activity code
7. Use information in featureName to decide corresponding lable to the data 


## Dependencies

```Run_analysis.R``` file will help you to install the dependencies automatically. It depends on ```reshape2``` and ```data.table```. 