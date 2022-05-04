# Stock-Price-Prediction
Stock Price Prediction and Forecasting Using Stacked LSTM

Steps followed:
1. Utilized AAPL Stock price of last 5 years till date from Tiingo Stocks & Financial Markets data API using pandas_datareader library
2. Preprocessed the data (handling nan values, scaling the data, reshaping it for LSTM)
3. Building a stack LSTM model 
4. Made the stock price prediction for the next 30 days by using the stacked LSTM model 
5. Can improve the model by using hyperparameter tuning for the number of days I can consider for the model training

