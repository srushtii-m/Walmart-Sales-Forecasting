# Walmart-Sales-Forecasting
This project focuses on forecasting weekly sales for a subset of Walmart stores using various machine learning and time series models.

The analysis covers models such as Ridge Regression, Random Forest, XGBoost, SARIMA, and LSTM, and explores how different factors like holidays, fuel prices, and temperature influence sales. The project also includes an extensive exploratory data analysis to understand the impact of holidays, fuel prices, temperature, and other factors on sales.

## Motivation
The goal of this project is to provide accurate sales forecasts for Walmart, enabling better inventory management, staffing, and financial planning. This is crucial for optimizing operations and enhancing customer satisfaction in the competitive retail landscape.

## Data
The dataset includes weekly sales data from 45 Walmart stores, along with associated store attributes and external factors such as holidays, temperature, CPI, and fuel prices. Special attention was given to data cleaning, particularly in handling missing values and anomalies.

## Model Development
Implementing various models and tuning them for optimal performance.
  - **SARIMA**: Adjusted for seasonality and stationarity.
  - **Ridge Regression**: Implemented with sklearn but showed high WMAE error.
  - **Random Forest and XGBoost Regressors**: Included hyperparameter tuning.
  - **LSTM and MLP Models**: Explored for deep learning approaches.

