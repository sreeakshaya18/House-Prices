# House-Prices
Summarizing what we have done in this notebook:


*   Removed columns with a large proportion of null values.
*   Filled the rest of the null values with the column mode.
*   Used one hot encoding and label encoding to categorical variables into numerical ones.
*   Removed features that have high correlation with each other.
*   Did feature scaling using Min Max Scaler.
*   Removed features whose absolute correlation with the target variable was very small.
*   Used p values from OLS for feature selection.
*   Also tried log transformations and feature selection using feature scores from SelectKBest, but they did not seem to help here.
*   Used OLS and Ridge regression models to predict.
*   Calculated cross validation error to find the best regularization parameter and to choose the final model.
