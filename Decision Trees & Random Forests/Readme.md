# Problem Statement

The Rain in Australia dataset contains about 10 years of daily weather observations from numerous Australian weather stations. As a data scientist at the Bureau of Meteorology, you are tasked with creating a fully-automated system that can use today's weather data for a given location to predict whether it will rain at the location tomorrow.
Dataset: https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package

# Results
A Random Forest model was trained on a time series dataset, which was partitioned into training, validation, and test sets based on dates. Numerical columns were pre-processed using imputation and scaling, while categorical columns were pre-processed using one-hot encoding. The model initially was overfitted, but was then tuned using Hyper-parameters such as max_leaf_nodes, max_depth, bootstrap etc. It finally reached an accuracy of 84.5% on Testing Datset
