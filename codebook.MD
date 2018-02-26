# Getting and Creating Data Course Project

## Source Data
Data was obtained from [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)

## R Program

The code used for the program followed these general steps:

1. Read, formatted, and import data into R with working directory 
2. Merge existing training and test data sets into one new data set
3. Extract measurements within the mean and standard deviation for each measurement
4. Use descriptive activity names for current data set activites
5. Assign appropriate data labels for new variables
6. Create second, independent data set with averages for each variable, activity, and subject
7. Extract data and create tidy data set file

## Output / Program Variables

* Subject are the identifiers for each activity
* Activity are the identifiers for each activity name performed
* measurement are the measurements for each activity
* mean  are the mean of each measurement mean / standard deviation
* run_analysis_tidy.txt is the text file containing final tidy data set

## Extracted Variables

Variable names from extracted data:

*  [1] "tBodyAcc-mean()-X"                   
*  [2] "tBodyAcc-mean()-Y"                   
*  [3] "tBodyAcc-mean()-Z"                   
*  [4] "tBodyAcc-std()-X"                    
*  [5] "tBodyAcc-std()-Y"                    
*  [6] "tBodyAcc-std()-Z"                    
*  [7] "tGravityAcc-mean()-X"                
*  [8] "tGravityAcc-mean()-Y"                
*  [9] "tGravityAcc-mean()-Z"                
* [10] "tGravityAcc-std()-X"                 
* [11] "tGravityAcc-std()-Y"                 
* [12] "tGravityAcc-std()-Z"                 
* [13] "tBodyAccJerk-mean()-X"               
* [14] "tBodyAccJerk-mean()-Y"               
* [15] "tBodyAccJerk-mean()-Z"               
* [16] "tBodyAccJerk-std()-X"                
* [17] "tBodyAccJerk-std()-Y"                
* [18] "tBodyAccJerk-std()-Z"                
* [19] "tBodyGyro-mean()-X"                  
* [20] "tBodyGyro-mean()-Y"                  
* [21] "tBodyGyro-mean()-Z"                  
* [22] "tBodyGyro-std()-X"                   
* [23] "tBodyGyro-std()-Y"                   
* [24] "tBodyGyro-std()-Z"                   
* [25] "tBodyGyroJerk-mean()-X"              
* [26] "tBodyGyroJerk-mean()-Y"              
* [27] "tBodyGyroJerk-mean()-Z"              
* [28] "tBodyGyroJerk-std()-X"               
* [29] "tBodyGyroJerk-std()-Y"               
* [30] "tBodyGyroJerk-std()-Z"               
* [31] "tBodyAccMag-mean()"                  
* [32] "tBodyAccMag-std()"                   
* [33] "tGravityAccMag-mean()"               
* [34] "tGravityAccMag-std()"                
* [35] "tBodyAccJerkMag-mean()"              
* [36] "tBodyAccJerkMag-std()"               
* [37] "tBodyGyroMag-mean()"                 
* [38] "tBodyGyroMag-std()"                  
* [39] "tBodyGyroJerkMag-mean()"             
* [40] "tBodyGyroJerkMag-std()"              
* [41] "fBodyAcc-mean()-X"                   
* [42] "fBodyAcc-mean()-Y"                   
* [43] "fBodyAcc-mean()-Z"                   
* [44] "fBodyAcc-std()-X"                    
* [45] "fBodyAcc-std()-Y"                    
* [46] "fBodyAcc-std()-Z"                    
* [47] "fBodyAcc-meanFreq()-X"               
* [48] "fBodyAcc-meanFreq()-Y"               
* [49] "fBodyAcc-meanFreq()-Z"               
* [50] "fBodyAccJerk-mean()-X"               
* [51] "fBodyAccJerk-mean()-Y"               
* [52] "fBodyAccJerk-mean()-Z"               
* [53] "fBodyAccJerk-std()-X"                
* [54] "fBodyAccJerk-std()-Y"                
* [55] "fBodyAccJerk-std()-Z"                
* [56] "fBodyAccJerk-meanFreq()-X"           
* [57] "fBodyAccJerk-meanFreq()-Y"           
* [58] "fBodyAccJerk-meanFreq()-Z"           
* [59] "fBodyGyro-mean()-X"                  
* [60] "fBodyGyro-mean()-Y"                  
* [61] "fBodyGyro-mean()-Z"                  
* [62] "fBodyGyro-std()-X"                   
* [63] "fBodyGyro-std()-Y"                   
* [64] "fBodyGyro-std()-Z"                   
* [65] "fBodyGyro-meanFreq()-X"              
* [66] "fBodyGyro-meanFreq()-Y"              
* [67] "fBodyGyro-meanFreq()-Z"              
* [68] "fBodyAccMag-mean()"                  
* [69] "fBodyAccMag-std()"                   
* [70] "fBodyAccMag-meanFreq()"              
* [71] "fBodyBodyAccJerkMag-mean()"          
* [72] "fBodyBodyAccJerkMag-std()"           
* [73] "fBodyBodyAccJerkMag-meanFreq()"      
* [74] "fBodyBodyGyroMag-mean()"             
* [75] "fBodyBodyGyroMag-std()"              
* [76] "fBodyBodyGyroMag-meanFreq()"         
* [77] "fBodyBodyGyroJerkMag-mean()"         
* [78] "fBodyBodyGyroJerkMag-std()"          
* [79] "fBodyBodyGyroJerkMag-meanFreq()"     
* [80] "angle(tBodyAccMean,gravity)"         
* [81] "angle(tBodyAccJerkMean),gravityMean)"
* [82] "angle(tBodyGyroMean,gravityMean)"    
* [83] "angle(tBodyGyroJerkMean,gravityMean)"
* [84] "angle(X,gravityMean)"                
* [85] "angle(Y,gravityMean)"                
* [86] "angle(Z,gravityMean)"                
* [87] "Activity"                            
* [88] "Subject"