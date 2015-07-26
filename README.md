# cleaning_data_project
The R script does the following steps 

Download the dataset from the web 
Loads the activity and feature info after unzipping the data 
Loads both the training and test datasets, keeping only those columns which can provide a mean or standard deviation
Loads the activity and subject data for each dataset, and merge those columns with the dataset
Merge the two datasets and convert the activity and subject columns into factors
Create a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.
The end result is shown in the file tidy.txt.
