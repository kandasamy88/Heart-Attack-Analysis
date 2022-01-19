# Heart-Attack-Analysis
Introduction
A heart attack occurs when an artery supplying your heart with blood and oxygen becomes blocked. A blood clot can form and block your arteries, causing a heart attack. This Heart Attack Analysis helps to understand the chance of attack occurrence in persons based on varied health conditions.
# Problem Definition
 Building a Predictive Model (Which features decide heart attack?)
 Evaluate the model.
 Refine the model, as appropriate
# Dataset
The dataset is Heart_Attack_Analysis_Data.csv. This data set contains data about hundreds of patients.
# Data Cleansing
The given Data is checked for the following:
1. Null Values - Not Available
2. Irrelevant Data - Not Available
3. Improper format - Not Available
# Understanding the Data
1. Statistical Descriptions: In order to have an overall picture of the data, some basic statistical descriptions were used to identify the various properties of the data.
2. Compared each factors/ columns with the target dataset
3. Provided bar plot for all eligible comparisons
# Outlier analysis
There are some extreme values observed in some of the quantitative variables and from healthcare domain perspective it seems obvious to get such values as patients with critical conditions can have abnormal values of these variables. So we have not treated these as outliers.
# Correlation of Data
The given Data has been correlated with the Target (State of having Heart Attack or not)
And found the almost all factors has relation except “Family History” and “Blood Sugar Level”, which has week correlation
Finding Best Predictive Model
The data has been split in to Train Data and Test Data (33%)
Using these Train and test data the following Models has been evaluated and checked for Accuracy
# PREDICTIVE MODEL
ACCURACY
Logistic Regression
85%
Support Vector Machine
88%
K-Nearest Neighbors
67%
Decision Tree
82%
Random Forest
88%
# Conclusion
Based on the data analysis and the accuracy of the predictive model, “Support Vector Machine” & “RANDOM FOREST” are found to provide best accuracy to predict the heart attack.
The Accuracy increases with the number of Test Set / Data Set for “RANDOM FOREST”
