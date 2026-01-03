# Leveraging Machine Learning to Predict Food Item Sales

## Project Overview

This project applies machine learning techniques to predict **daily sales quantities for a single Walmart food product** using historical sales data. The dataset originates from the **Walmart M5 Forecasting Competition** and spans approximately **5.4 years** (January 2011 to June 2016).

The objective is to improve demand forecasting by leveraging **time-series modeling**, **autoregressive (lagged) features**, and a range of **machine learning models**. By incorporating temporal features, event indicators, pricing information, and sales lags, the project evaluates how effectively different models capture complex sales patterns and outperform a naive baseline.

Several models were trained and compared, including **regularized linear models**, **Random Forests**, and **XGBoost**. Model performance was evaluated using **Root Mean Squared Error (RMSE)**, with careful handling of time dependency through **non-shuffled train–test splits** and **TimeSeriesSplit cross-validation** to prevent data leakage.

---

## Tech Stack

### Python Version

- **Python**: 3.12.10

### Packages and Versions

- **numpy**: 2.2.5  
- **pandas**: 2.2.3  
- **polars**: 1.27.1  
- **matplotlib**: 3.10.1  
- **seaborn**: 0.13.2  
- **scikit-learn**: 1.6.1  
- **xgboost (py-xgboost)**: 3.0.0  
- **shap**: 0.47.2  
- **duckdb**: latest (conda-forge)  
- **pandas-flavor**: 0.7.0  
- **pingouin**: 0.5.5  
- **tabulate**: 0.9.0  
- **xarray**: 2025.11.0  
- **jupyter**: latest (conda-forge)  
- **pickle**: Python standard library  

All dependencies were installed via **conda-forge**.
