# Stock Price Prediction using ARIMA

## Objective
The objective of this project is to predict stock prices using the ARIMA (AutoRegressive Integrated Moving Average) model with historical Nifty50 index data from 2017 to 2023.

## Description
This repository contains a Python script that applies the ARIMA model to predict stock prices based on historical data. The Nifty50 index data is used for the period 2017-2023.

## Methodology
1. **Data Collection:** Historical Nifty50 index data from 2017 to 2023 was obtained from yahoo finance.

2. **Data Visualization:** The data was visualized to gain insights into the stock price trends over time.

3. **Stationarity Check:** The Augmented Dickey-Fuller (ADF) test was used to assess the stationarity of the time series data. Data was differenced twice to achieve stationarity.

4. **ARIMA Parameter Selection:** The optimal ARIMA model parameters (p, d, q) were determined using the Akaike Information Criterion (AIC) matrix.

5. **Model Fitting:** The ARIMA model was trained on data from 2017 to 2022. Subsequently, it was used to forecast stock prices for the period 2022 to 2023.

## Results
The ARIMA model provided predictions for stock prices, but its accuracy was limited due to the inherent complexity and volatility of the stock market. It's important to note that stock prices are influenced by various external factors beyond historical prices, which the ARIMA model does not consider. Hence, while the ARIMA model can provide insights, it may not be the most accurate tool for stock price forecasting.


