# Cryptocurrency Price Forecasting with LSTM

This project uses an LSTM model to forecast the next 30 days of prices for major cryptocurrencies, including BTC, ETH, XMR, XLM, BCH, and XRP. The predictions are visualized in a Power BI dashboard to provide clear business insights.

##  Files
- dataset -https://www.kaggle.com/datasets/jessevent/all-crypto-currencies
- `cryptocurrency_prediction.py` – Python script for data cleaning, LSTM modeling, and forecasting.
- `crypto_all_actual_forecast.csv` – Combined CSV of actual and forecasted prices for all coins.
- `Dashboard.pbix` – Power BI dashboard showing historical trends and future price forecasts.

##  Project Summary

1. **Data cleaning and preparation:** Filtered each coin's data, removed zeros or missing values, and scaled closing prices.
2. **Model building:** Trained an LSTM model using the past 60 days to predict the next day's price.
3. **Forecasting:** Generated 30-day future price forecasts for each cryptocurrency.
4. **Dashboarding:** Combined forecasts into a single CSV for Power BI visualization, comparing actual vs forecast prices.

##  Dashboard Overview

The Power BI dashboard shows:

- Historical closing prices for each cryptocurrency.
- Forecasted prices for the next 30 days.
- Comparison of actual and predicted prices to evaluate model performance.

##  Usage

1. Run the Python script to generate forecast CSV files.
2. Load `crypto_all_actual_forecast.csv` into the Power BI dashboard.
3. Explore trends and forecasts interactively for business insights or trading strategies.

---

###  **Dashboard Short Description**

> This dashboard shows historical trends and 30-day forecasts for major cryptocurrencies using LSTM models. It combines actual and predicted prices to help analyse market movements and plan future strategies efficiently.
