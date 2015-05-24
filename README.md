# Getting and Cleaning Data Course Project README

This repo contains run_analysis.R, a codebook and this README. The run_analysis.R file is designed to read the datasets enclosed in the  UCI HAR Dataset (see http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones) and convert it to a tidy dataset that averages the accelerometer and gyroscope 3-axial raw signals for each subject and activity the subject is doing. 

This was done as the course project for the "Getting and Cleaning Data" course in Coursera which is part of the "Data Science" specialization track.

The course projects states that the run_analysis.R file must do the following:
  1. Merges the training and the test sets to create one data set.
  2. Extracts only the measurements on the mean and standard deviation for each measurement. 
  3. Uses descriptive activity names to name the activities in the data set
  4. Appropriately labels the data set with descriptive variable names. 
  5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

# R Code and Dependencies   
The code that fulfills these requirements is in the run_analysis.R file found in this repository. The output from this file is a file called tidy_data.txt.

The code is written such that the data is already downloaded to your computer. The R file can be easily modified to reflect the location of the working directory. 

The R file was run on R version 3.1.3 (2015-03-09) -- "Smooth Sidewalk", and the platform is x86_64-w64-mingw32/x64 (64-bit). The R file assumes that the user has the "plyr" package. 

The codebook is available in this repository and it despcribes the data collection, variables, and the transformations that were performed on the data. 
