

Information about the study design can be found in:

info/study_design.txt

There are 8 data files (1 to 7 below) used to generate the final tidy data set:

Both of these files contain a single column of data that represents the chosen person or 'subject'

    1, subject_test.txt
    2, subject_train.txt

Both of these files contain a single column of data that represents the activity being undertaken

    3, y_test.txt
    4, y_train.txt

These files contain the 561 columns, each column being an element of the 'feature vector' described in (info/study_design.txt & info/features_info.txt)

    5, X_test.txt
    6, X_train.txt

The names of the individual columns are specified in:

    7, info/features.txt

This file contains a description of each activity

    8, activity_labels.txt

The tidy data set created is called "activities.txt". It contains an average (over subject and activity)
of all of the mean and standard deviation variables listed in "info/features.txt". The variable
names are the same as those in "info/features.txt" only they have had the word average appended to them.




