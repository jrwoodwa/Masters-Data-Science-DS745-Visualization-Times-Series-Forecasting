# Masters-Data-Science-DS745-Visualization-Times-Series-Forecasting

This project applies ARIMA to forecast GameStop (GME) stock prices using five years of historical data. The dataset, sourced from Yahoo! Finance, includes adjusted closing prices and volume. Missing weekend values are imputed accordingly.

Key steps:

- Data preprocessing with imputations.
- ARIMA modeling with auto.arima in R.
- Tuning hyperparameters and testing seasonality.
- Incorporating volume as an exogenous variable.

Findings: The best ARIMA model suggests a pessimistic forecast, cautioning against reliance on short-term predictions due to volatility.
