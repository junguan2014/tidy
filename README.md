# Tidy project
Download the data source and put into a folder on your local drive. You'll have a UCI HAR Dataset folder.
Put run_analysis.R in the parent folder of UCI HAR Dataset, then set it as your working directory using setwd() function in RStudio.
Run source("run_analysis.R"), then it will generate a new file tiny_data.txt in your working directory.

The process including below steps:
1. read all data
2. create features_filter to filter out non mean/std rows. and use features_filter to filter train and test data set.
3. assign meaningful column names to all data sets
4. combine train and test data together
5. use melt and dcast to calculate final results.