# CleaningData - 


The goal is to prepare tidy data that can be used for later analysis. 

1) a tidy data set  
2) a link to a Github repository with the script for performing the analysis, and 
3) a code book that describes the variables, the data, and any transformations or work that was performed to clean up the data called CodeBook.md.  

Created one R script called run_analysis.R that does the following.
• Merges the training and the test sets to create one data set.
• Extracts only the measurements on the mean and standard deviation for each measurement.
• Uses descriptive activity names to name the activities in the data set
• Appropriately labels the data set with descriptive activity names.
• Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

Notes

• Used the plyr & reshape2 packages.
• Dataset was unzipped in the current directory.


Usage
$ Rscript run_analysis.R

creates 2 files
1. tidydata.txt 
2. tidymeandata.txt
