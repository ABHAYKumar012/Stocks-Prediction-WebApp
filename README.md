# Stock Prediction App

The Stock Prediction App is a web application built with Streamlit that allows users to select a stock from a list of popular stocks and generate a forecast for the stock's closing prices for a specified number of years. The app uses historical stock data from Yahoo Finance and applies the Prophet forecasting model to predict future stock prices.

## Features

- **Select Stock**: Choose a stock from a predefined list including GOOG, AAPL, MSFT, GME, AMZN, JD, TSLA, and ADBE.
- **Set Prediction Period**: Use a slider to set the number of years for the prediction (up to 4 years).
- **View Raw Data**: Display the most recent raw data for the selected stock.
- **Plot Time Series Data**: Visualize the historical open and close prices of the selected stock.
- **Generate Forecast**: Forecast future stock prices using the Prophet model.
- **View Forecast Components**: Display the forecast components such as trend, weekly seasonality, and yearly seasonality.

## Prerequisites

Ensure you have the following installed:

- Python 3.x
- Streamlit
- yfinance
- fbprophet
- plotly

You can install the required libraries using pip:

```bash
conda create -n stock_forecast python=3.9

conda activate stock_forecast

conda install -c conda-forge streamlit yfinance prophet plotly
