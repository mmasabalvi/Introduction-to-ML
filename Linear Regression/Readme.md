# Problem Statement

ACME Insurance Inc. offers affordable health insurance to thousands of customer all over the United States. As the lead data scientist at ACME, you're tasked with creating an automated system to estimate the annual medical expenditure for new customers, using information such as their age, sex, BMI, children, smoking habits and region of residence.

Estimates from your system will be used to determine the annual insurance premium (amount paid every month) offered to the customer. Due to regulatory requirements, you must be able to explain why your system outputs a certain prediction.

You're given a CSV file containing verified historical data, consisting of the aforementioned information and the actual medical charges incurred by over 1300 customers.

# Results

A Linear Regression Model is used to predict annual medical charges using different features provided in the Dataset. Categorical Features are also converted, using techniques such as one hot encoding. The RMSE Loss function is used, and loss is calculated at 4684.433 $, due to a large number of outliers
 
