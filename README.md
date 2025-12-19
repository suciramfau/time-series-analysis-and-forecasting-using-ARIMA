# Time Series Analysis and Forecasting Using ARIMA

This mini case study demonstrates a complete time series analysis and forecasting workflow using ARIMA, focusing on identifying temporal patterns, handling non-stationary data, and generating reliable forecasts.

## Objective
- Analyze trend and seasonality patterns in time series data
- Determine whether the series is stationary
- Apply appropriate transformations to achieve stationarity
- Build an ARIMA-based forecasting model
- Generate short-term future forecasts

## Dataset
Monthly Anti-diabetic Drug Sales Dataset (Australia)  
Source: https://github.com/selva86/datasets

- Frequency: Monthly
- Target variable: Sales

## Key Analysis Steps
- Time series visualization to identify trend and seasonality
- Seasonal decomposition (additive vs multiplicative)
- Stationarity testing using Augmented Dickey-Fuller (ADF) test
- Data transformation using log transformation and differencing
- Train–test split for model evaluation
- ARIMA modeling using Auto ARIMA
- Model evaluation using MAE and RMSE
- Future forecasting for the next 12 months

## Key Insights
- The data exhibits a clear upward trend and strong yearly seasonality
- The original series is non-stationary
- Log transformation and first-order differencing successfully achieve stationarity
- ARIMA effectively captures both trend and seasonal patterns
- The model produces stable and interpretable forecasts

## Tools
- Python
- Pandas
- NumPy
- Statsmodels
- pmdarima
- Matplotlib
- Scikit-learn

## Outcome
This project highlights the importance of stationarity, transformation, and seasonal analysis in time series forecasting, and demonstrates how ARIMA models can be applied to real-world temporal data.

This mini case study is part of the **Core Modeling Techniques** section of my Data Science portfolio.
