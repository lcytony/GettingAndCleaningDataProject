#Code Book
##Variable list and descriptions
* subject: experiment subject ID
* activityName: the actibity name the corresponding subject was doing
* Domain: time signal or frequency signal
* Acceleration: type of acceleration signal
* Equipment: measuring instrument
* Jerk:jerk signal
* Magnitude: magnitude signal
* Stats: statistics calculated (mean or stdev)
* Axis: 3-axial signals
* count: count of data points used in average calculation
* average: average of each statistics per activity per subject

## Transformation details

There are 5 parts:

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names.
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## How ```Run_analysis.R``` implements the above steps:
* Require ```reshape2``` and ```data.table``` librareis.
* Load both test and train data
* Load the features and activity labels.
* Extract the mean and standard deviation column names and data.
* Process the data. There are two parts processing test and train data respectively.
* Merge data set.
