# Stock Market Forecasting App

This repository contains a **Stock Market Forecasting App** created using Streamlit. The app enables users to forecast the stock market prices of selected companies using various machine learning models. The key features and functionalities of the app are as follows:

## Features

1. **Interactive User Interface**: 
   - Users can select the company ticker, start date, and end date for stock data.
   - Sidebar options for model selection and parameter inputs.

2. **Data Visualization**: 
   - Visualize stock prices over the selected date range using Plotly.
   - Decomposition of time series data into trend, seasonality, and residuals.

3. **Model Selection**:
   - **SARIMA**: Seasonal AutoRegressive Integrated Moving Average.
   - **Random Forest**: Ensemble learning method for regression.
   - **LSTM**: Long Short-Term Memory neural network.
   - **Prophet**: Facebook’s time series forecasting model.

4. **Forecasting**:
   - Generate future stock price predictions using the selected model.
   - Display actual vs. predicted stock prices on interactive plots.

## Libraries Used

- **Data Handling**: 
  - `pandas`, `numpy`
- **Visualization**:
  - `matplotlib`, `seaborn`, `plotly`
- **Time Series Analysis**:
  - `statsmodels`, `Prophet`
- **Machine Learning**:
  - `RandomForestRegressor`, `mean_squared_error` from `sklearn`
  - `Sequential`, `LSTM`, `Dense` from `keras`
- **Date and Time Handling**:
  - `datetime`

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/stock-market-forecasting-app.git
   cd stock-market-forecasting-app

