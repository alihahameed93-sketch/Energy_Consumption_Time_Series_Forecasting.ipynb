# Energy Consumption Time Series Forecasting

## Objective
The objective of this project is to forecast future energy
consumption using historical time series data. Accurate
energy forecasting helps in planning and optimizing power
generation and usage.

## Dataset
Electric power consumption time series data fetched directly
from an official public data source using Python.
The dataset contains monthly energy consumption values.

## Approach
- Data loading and preprocessing
- Time series visualization
- Train-test split based on time
- Forecasting using ARIMA, Prophet, and XGBoost
- Model evaluation using MAE and RMSE
- Visualization of actual vs forecasted values

## Tools & Technologies
- Python
- Google Colab
- Pandas, NumPy
- Matplotlib
- Statsmodels (ARIMA)
- Prophet
- XGBoost

## Results
All three models were able to capture the overall trend
in energy consumption. Prophet and XGBoost showed
better performance for long-term forecasting, while
ARIMA performed well for short-term predictions.

## Conclusion
Time series forecasting techniques can effectively model
energy consumption patterns. Comparing multiple models
helps identify the most suitable approach for forecasting
future energy usage.
