Analysis File Description
The run_analysis.R can be run as long as setting your working directory to the UCI HAR Dataset folder. Dplyr package was required to run this script.

Analysis will read all the test data and train data merge them into one data set. Each variables were names accordingly based on the features listed in the features.txt file.

Using the combined data set, independent tidy data set with the average of each variable for each activity and each subject was created and written into tidydataset.txt file.
