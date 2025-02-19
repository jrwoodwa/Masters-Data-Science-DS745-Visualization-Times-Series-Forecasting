# Masters-Data-Science-DS745-Visualization-Times-Series-Forecasting

This project applies ARIMA to forecast GameStop (GME) stock prices using five years of historical data. The dataset, sourced from Yahoo! Finance, includes adjusted closing prices and volume. Missing weekend values are imputed accordingly.

Key steps:

- Data preprocessing with imputations.
- ARIMA modeling with auto.arima in R.
- Tuning hyperparameters and testing seasonality.
- Incorporating volume as an exogenous variable.

Findings: The best ARIMA model suggested a pessimistic forecast, cautioning against reliance on short-term predictions due to volatility.

Comparisons to what transpired:
![image](https://github.com/user-attachments/assets/cb6f9ad3-80b9-40b1-ab43-5a2243bb6170)
