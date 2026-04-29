# Time Series Forecasting – Airline Passengers ✈️

## Objective
Forecast monthly airline passenger demand using ARIMA and SARIMAX models.

## Dataset
- 144 monthly records (1949–1960)
- Source: [Kaggle](https://www.kaggle.com/datasets/rakannimer/air-passengers)

## Key Steps
- ADF test to validate non-stationarity
- Multiplicative seasonal decomposition
- Log transformation to stabilize variance
- Trained and compared ARIMA(5,1,0) vs SARIMAX(1,1,1)(1,1,1,12)
- Evaluated using MAE, MSE, RMSE on 12-month holdout

## Tech Stack
Python, Statsmodels, Pandas, Matplotlib
