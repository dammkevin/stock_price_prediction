# Stock Price Prediction for Amazon (AMZN)

This project predicts Amazon's stock price for a specified future date using the past 60 days of historical stock data. Additionally, it verifies the actual stock price for a given date from Yahoo Finance.

## Introduction
This project implements a stock price prediction model using historical stock data from Yahoo Finance. It dynamically fetches the required data, processes it for machine learning, and predicts the stock price using an LSTM neural network.

In addition, the project includes functionality to fetch the actual stock price for a given date to compare the predicted value against real-world data.

## Features
- Fetch historical stock data dynamically using `yfinance`.
- Preprocess stock data for machine learning predictions.
- Use an LSTM (Long Short-Term Memory) model to predict stock prices.
- Dynamically handle column variations in stock data (e.g., `'Close'`, `'Close_AMZN'`).
- Validate predictions by fetching actual stock prices for the target date.

## Technologies Used
- **Python 3.x**
- **Libraries:**
  - `yfinance` - Fetch stock data from Yahoo Finance.
  - `NumPy` - Numerical computations.
  - `pandas` - Data manipulation and analysis.
  - `scikit-learn` - Data preprocessing (e.g., scaling).
  - `TensorFlow/Keras` - Build and train the LSTM model.
