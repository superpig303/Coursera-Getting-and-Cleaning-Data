Coursera-Getting-and-Cleaning-Data
==================================

Overall
This repository is the course project for the Coursera course "Getting and Cleaning data".

Raw data
The features (561 of them) are unlabeled and can be found in the x_test.txt. 
The activity labels are in the y_test.txt file. 
The test subjects are in the sj_test.txt file.
For training set, it is the same.

Code book
The codebook.md file includes the explanation on the transformations performed, the resulting data and the variables.

The script
A script called run_analysis.R was created to merge the test and training sets together.
After testing and training data were merged, labels are added.
Columns on the mean and standard deviation are kept.
A tidy data set which contains the means of all the columns per test subject and per activity was generated finally.
