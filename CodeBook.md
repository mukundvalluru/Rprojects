# CodeBook

## Overview

This codebook describes the variables, the data, and any transformations or work performed to clean up the Human Activity Recognition Using Smartphones dataset.

## Variables

- `subject`: The ID of the subject (1-30).
- `activity`: The activity performed (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING).

## Measurements

- `TimeBodyAccelerometerMeanX`
- `TimeBodyAccelerometerMeanY`
- `TimeBodyAccelerometerMeanZ`
- ...
- `FrequencyBodyGyroscopeSTDZ`

## Transformations

1. Merged the training and test sets.
2. Extracted measurements on mean and standard deviation.
3. Used descriptive activity names.
4. Labeled the data set with descriptive variable names.
5. Created a second tidy data set with the average of each variable for each activity and each subject.
