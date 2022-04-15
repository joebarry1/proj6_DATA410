# Project 6

## There Can Only Be One Winner: Testing Class Imbalance Techniques on NCAA March Madness Data

Every year, the winner of the NCAA College Basketball season is decided in a 68 team tournament. From this large pool, in three weeks of basketball, one winner is decided. There is good money in being able to predict this winner; billions of dollars are gambled every year on the tournament, justifiably named “March Madness”. However, given how few of the initial teams end up successful, modeling this data can be difficult, as it presents a classic class imbalance problem.

I have collected a dataset of 6 years of March Madness placements, along with the team statistics throughout those seasons. In my project, I will use this data to determine which technique, between ADASYN and SMOTE, is better at predicting successful March Madness data. While research has been done on this topic, the nature of the imbalance in this data is different (there are multiple classes for each finishing placement in the tournament, each differently imbalanced). Using a baseline of a Random Forest model without any imbalance techniques applied, I will see which of these models is better at estimating the data using various metrics (accuracy, recall, F-score, etc.). 

[Here is a link to the dataset!](For_Python.csv)
