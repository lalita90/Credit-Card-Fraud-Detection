# Credit-Card-Fraud-Detection
Anomaly detection using credit card transaction data

In this project, I will implement machine learning approaches useful for identifying fraud using credit card transaction dataset. I will also address the challenges associated with imbalanced class problem. 
I am using Kaggle dataset for our project which can be found at the following link:
https://www.kaggle.com/mlg-ulb/creditcardfraud

It contains 284807 datapoints and 31 features which include our class label as well. The first column is Time which represents the number of seconds elapsed between current transaction and the first transaction in the dataset. This is a binary classification problem where 0- no fraud and 1- fraud. Also, it suffers from imbalanced class problem. As we can see out of 284807 data points we have only 492 data points linked with fraud transactions. So instead of just focusing on the accuracy of the model we will have to carefully choose other performance metrics such as Precision, Recall and F1 score which can be a true performance indicator.


**Outline:**
1. Understanding the data
2. Data Preprocessing
3. Sampling data to deal with imbalanced class
4. Training and testing the model
