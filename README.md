**Stock Price Prediction using LSTM (Apple Inc.)**
This project demonstrates how to predict stock prices using Long Short-Term Memory (LSTM) neural networks in Python. Using historical stock prices of Apple Inc. (AAPL), this project builds a model that forecasts future closing prices based on past trends.

**Project Overview:**
1. Objective: Predict future closing prices of Apple Inc. using historical data.
2. Data Source: Yahoo Finance (yfinance library).
3. Model: LSTM (Long Short-Term Memory) neural network.
4. Period: November 26, 2019 – Present.
5. Tools & Libraries: Python, NumPy, Pandas, Matplotlib, Scikit-learn, Keras, yfinance.

**Features:**
1. Fetches historical stock price data from Yahoo Finance.
2. Cleans and preprocesses the data (drops unnecessary columns, handles dates).
3. Normalizes data using MinMaxScaler.
4. Creates sequences of past 60 days to predict the next day’s closing price.
5. Builds and trains an LSTM model with two LSTM layers and a Dense output layer.
6. Predicts stock prices and visualizes both actual and predicted prices.
7. Calculates performance metrics (Root Mean Squared Error).

**Results:**
The model predicts the closing price of Apple Inc. with a Root Mean Squared Error (RMSE) of approximately 9.50 USD. The predictions closely follow the trend of actual stock prices, demonstrating the potential of LSTM for time-series forecasting.

**Visualizations:**
The project includes plots of:
1. Historical closing price
2. Training and test data
3. Predicted vs actual stock prices
