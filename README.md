# Stock Price Prediction

A machine learning project to predict stock prices using historical data stored in a CSV file. The project utilizes Python, TensorFlow, and Jupyter notebooks, and can be run in Google Colab.

## Dataset

The dataset contains historical stock prices with the following columns:
- **Date**: The date of the stock price data.
- **Open**: The opening price of the stock.
- **High**: The highest price of the stock on that date.
- **Low**: The lowest price of the stock on that date.
- **Close**: The closing price of the stock on that date.
- **Volume**: The trading volume of the stock on that date.
- **Dividents**: The Dividents of the stock on that date.
- **Stock-Splits**: The Stock-Splits of the stock on that date.

## Features

- **Data Preprocessing**: Cleans and prepares data for training using MinMaxScaler.
- **Model Training**: Uses LSTM neural networks for predicting future stock prices.
- **Evaluation**: Evaluates model performance using appropriate metrics.
- **Visualization**: Plots historical and predicted stock prices.

