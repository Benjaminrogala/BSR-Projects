# BSR-Projects
This project was done in an attempt to see what i can create in a weekend, this is not financial advice, nor should these models be considered particularly accurate for predicting stock prices



Stock Price Prediction Using Linear Regression

Overview

This project predicts future stock prices for any stock using historical data and a linear regression model. The user specifies a date range, and the program forecasts stock prices for 30,60,90 business days into the future based on the last available data point.

Features

Fetches historical stock price data using yfinance

Trains a linear regression model to predict stock prices

Monte Carlo Visualization

Risk Frontiers

Sharpe Ratios for stocks

Forecasts stock prices for the next 30 business days

Visualizes predictions with Matplotlib



Technologies Used

Python
Yahoo Finance API (yfinance) – for fetching stock price data
Pandas – for data processing
Scikit-learn – for linear regression modeling
Matplotlib – for visualization
NumPy – for numerical computations
Results and Accuracy

The model's accuracy is evaluated using:

Mean Squared Error (MSE)
R² Score
