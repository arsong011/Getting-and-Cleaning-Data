## Getting and Cleaning Data - peer assessment project    
## The original data was transformed by   
Merging the training and the test sets to create one data set.    
Extracting only the measurements on the mean and standard deviation for each measurement.     
Using descriptive activity names to name the activities in the data set     
Appropriately labeling the data set with descriptive activity names.     
Creating a second, independent tidy data set with the average of each variable for each activity and each subject.      
## About R script      
File with R code "run_analysis.R" perform 5 following steps (in accordance assigned task of course work)      
    
## About variables:    
subjectTrain, activityTrain, subjectTest, activityTest, featuresTrain and featuresTest contain the data from the downloaded files.     
subject, activity and features merge the previous datasets to further analysis.      
features contains the correct names for the extractData, which are applied to the column names stored in   
