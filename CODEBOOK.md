Information about the study design can be found in:

info/study_design.txt

There are 7 data files (1 to 7 below) used to generate the final tidy data set:

Both of these files contain a single column of data that represents the chosen person or 'subject'

* 1, subject_test.txt
* 2, subject_train.txt

Both of these files contain a single column of data that represents the activity being undertaken

* 3, y_test.txt
* 4, y_train.txt

These files contain the 561 columns, each column being an element of the 'feature vector' described in (info/study_design.txt & info/features_info.txt)

* 5, X_test.txt
* 6, X_train.txt

The names of the individual columns are specified in:

info/features.txt

This file contains a description of each activity

* 7, activity_labels.txt

The following variables have been created in the final tidy data set:

Subject - Number of subject undertaking activity
Activity - Activity being undertaken
Average x body acc mean  - average x direction acceleration means
Average y body acc mean  - average y direction acceleration means 
Average z body acc mean  - average z direction acceleration means 
Average x body acc std  - average x direction acceleration stds 
Average y body acc std  - average y direction acceleration stds
Average z body acc std  - average z direction acceleration stds
