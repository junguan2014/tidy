#CodeBook for Tidy project

The data source
* Original data: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
* Original description of the dataset: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Vairables:
activity_labels
features
X_test
y_test
subject_test
X_train
subject_train 

The process including below steps:
1. read all data
2. create features_filter to filter out non mean/std rows. and use features_filter to filter train and test data set.
3. assign meaningful column names to all data sets
4. combine train and test data together
5. use melt and dcast to calculate final results.