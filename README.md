# SRMIST Quantum Computing Club - Technical Task

## Overview

This project focuses on data analysis and modeling using give market dataset. The goal is to perform both regression and classification tasks to analyze and predict stock prices and market movements.

## Data Description

The dataset used in this project is `nifty_500.csv`, which includes various features related to stock market performance:

### Features

- **Open:** Opening price of the stock
- **High:** Highest price of the stock during the trading period
- **Low:** Lowest price of the stock during the trading period
- **Previous Close:** Closing price of the stock from the previous trading day
- **Share Volume:** Number of shares traded
- **Value (Indian Rupee):** Total traded value in Indian Rupees
- **52 Week High:** Highest price of the stock in the last 52 weeks
- **52 Week Low:** Lowest price of the stock in the last 52 weeks
- **365 Day Percentage Change:** Percentage change in stock price over the last 365 days
- **30 Day Percentage Change:** Percentage change in stock price over the last 30 days
- **Percentage Change:** Percentage change in stock price for the current period

## Data Preprocessing

- **Encoding:** Categorical variables 'Series' and 'Industry' were one-hot encoded to convert them into numerical format.
- **Standardization:** Numerical features 'Open', 'High', and 'Low' were standardized using RobustScaler to handle outliers.

## Modeling

### Regression Models

1. **Linear Regression**
   - **Evaluation Metrics:**
     - Mean Squared Error (MSE): `[MSE value]`
     - R² Score: `[R² value]`

2. **Random Forest Regressor**
   - **Evaluation Metrics:**
     - Mean Squared Error (MSE): `[MSE value]`
     - R² Score: `[R² value]`

### Classification Models

1. **Support Vector Machine (SVM)**
   - Optimized using GridSearchCV for the best parameters.
   - **Evaluation Metrics:**
     - Accuracy: `[Accuracy value]`
     - Precision: `[Precision value]`
     - Recall: `[Recall value]`
     - F1 Score: `[F1 Score value]`

2. **Linear SVM**
   - Optimized using GridSearchCV for the best parameters.
   - **Evaluation Metrics:**
     - Accuracy: `[Accuracy value]`
     - Precision: `[Precision value]`
     - Recall: `[Recall value]`
     - F1 Score: `[F1 Score value]`

3. **Random Forest Classifier**
   - Feature selection was performed using Recursive Feature Elimination (RFE).
   - **Evaluation Metrics:**
     - Accuracy: `[Accuracy value]`
     - Precision: `[Precision value]`
     - Recall: `[Recall value]`
     - F1 Score: `[F1 Score value]`

## Results

### Regression Model Results

- **Linear Regression:**
  - Mean Squared Error: `[MSE value]`
  - R² Score: `[R² value]`

- **Random Forest Regressor:**
  - Mean Squared Error: `[MSE value]`
  - R² Score: `[R² value]`

### Classification Model Results

- **SVM:**
  - Accuracy: `[Accuracy value]`
  - Precision: `[Precision value]`
  - Recall: `[Recall value]`
  - F1 Score: `[F1 Score value]`

- **Linear SVM:**
  - Accuracy: `[Accuracy value]`
  - Precision: `[Precision value]`
  - Recall: `[Recall value]`
  - F1 Score: `[F1 Score value]`

- **Random Forest Classifier:**
  - Accuracy: `[Accuracy value]`
  - Precision: `[Precision value]`
  - Recall: `[Recall value]`
  - F1 Score: `[F1 Score value]`

## Visualizations

- **Regression Plot:** Shows the relationship between actual and predicted stock prices.
- **Residual Plot:** Displays residuals for the Random Forest Regressor.
- **Confusion Matrix:** Visualizes the performance of the Random Forest Classifier.

## Comparison of Models

A comprehensive comparison of regression and classification models was conducted to evaluate their performance in predicting stock market trends.
