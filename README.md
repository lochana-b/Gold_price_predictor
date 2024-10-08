# Gold-Price-Predictor
# Introduction

This repository contains code for forecasting the price of gold using various time series forecasting methods. The dataset used is the daily price of gold in USD from 1950-01 to 2020-07.

# Dataset

The Monthly Gold Price dataset used for this analysis is the daily price of gold in USD from 1950-01 to 2020-07. The dataset contains 847 observations with 2 columns - Date and Price.

# Forecasting Models

Linear Regression Model

Naive Model

Exponential Smoothing Model

For the Linear Regression Model, the dataset was split into training and testing sets. The Linear Regression Model was fit on the training data and used to predict the gold prices for the test data. The mean absolute percentage error (MAPE) was used to evaluate the model's performance.

For the Naive Model, the last value of the training set was used to predict the gold prices for the test data. The MAPE was again used to evaluate the model's performance.

For the Exponential Smoothing Model, the statsmodels package was used to fit an Exponential Smoothing Model on the entire dataset. The model was then used to predict the gold prices for the test data. The 95% confidence intervals for the predictions were also calculated. The MAPE was again used to evaluate the model's performance.

# Results

The results of the three models were compared based on their MAPE scores. The Exponential Smoothing Model performed the best with a MAPE score of 17.235%.

# Conclusion

The Exponential Smoothing Model was used to predict the gold prices for the period 2020-08 to 2025-02. The predicted prices are stored in a CSV file named gold_monthly_csv.csv.

