# EUR/USD Pice Prediction 
In this project, we aim to predict the future price of the currency exchange rate of Euro (EUR) against US Dollar (USD) using time series analysis and forecasting techniques. 
Here, we poerform time series analysis which is a statistical approach that is used to analyze the data that varies over time, such as stock prices, exchange rates, and weather patterns. By analyzing the historical data of the EUR/USD exchange rate, we can identify trends, patterns, and seasonality, which can then be used to make predictions about future values. Here we have used advanced statistical and machine learning techniques to build a predictive model that can provide accurate and reliable forecasts. Our goal is to provide valuable insights and predictions to assist traders, investors, and market participants in making informed decisions regarding the EUR/USD exchange rate.

For this project we have taken reference from the book "Jason Brownlee - Introduction to Time Series Forecasting with Python" for our approach and basic analysis. We have focused on differnt chapters to bring about more understanding and meaning from our EURUSD Dataset.

# Process Followed
- Exploratory Data Analaysis
- Feature Engineering (where we have inclueded few cross overs as well)
- Data Visualization
- Resampling and Interpolation
- Transformation (Square Root, Log, Box-Cox)
- Testing for stationarity
- Converting Non Stationary Time Series to stationary
- Moving Average Smootheing
- Testing For White Noise
- Testing for Random Walk
- Decomposing Time Series Data (Additive and Multiplicative)
- Removing Trends (Detrend)
- Remvoing Seasonality (Deseasonalising)
- Stationarity in Time Series Data
- Backtesting Models (Train-Test split, Multiple Train-Test split, Walk Forward Validation)
- Different Arima Models and Testing them for Accuracy

# Time Series Analysis and Forecasting models Used:
  - ARIMA
  - Auto ARIMA
  - Seasonal ARIMA 
  - Holt Winter
  - Multivariate Data Analysis - VARMAX and Random Forest Regressor

# Prediction Results:
  <img width="500" alt="image" src="https://user-images.githubusercontent.com/82747267/219603994-c09606f2-cc4e-4558-b3fb-357a6387f2b8.png" >
  HOLT WINTER model yields the best result with a MAPE score of 0.02
