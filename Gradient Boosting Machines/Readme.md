# Problem Statement

This Dataset is taken from Rossmann Store Sales competition on Kaggle.
Link: https://www.kaggle.com/c/rossmann-store-sales/data

Rossmann operates over 3,000 drug stores in 7 European countries. Currently, Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality.

With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied. You are provided with historical sales data for 1,115 Rossmann stores. The task is to forecast the "Sales" column for the test set. Note that some stores in the dataset were temporarily closed for refurbishment.

# Results 


First, the dataset underwent a pre-processing phase, where multiple datasets were merged to create a more comprehensive and unified dataset. Next, feature engineering was applied, adding new columns of data to simplify the training process for the model. Numerical and categorical columns were handled appropriately using techniques such as scaling and one-hot encoding. A Gradient Boosting Machine (GBM) model was then trained and evaluated using the Root Mean Square Error (RMSE) loss function. K-Fold cross-validation was employed to validate the model. Finally, after extensive experimentation, hyperparameters were tuned to develop the model with the best possible performance.
