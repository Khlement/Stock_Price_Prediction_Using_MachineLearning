# Stock Price Prediction Using MachineLearning
This is a Python script that implements a Long Short-Term Memory (LSTM) model to predict the adjusted close price of a stock using high price, low price, open price, close price, volume, and adjusted close price from historical stock data. Historical stock data of Samsung Electronics Co., Ltd. (KS: 005930) was used by loading it through Yahoo Finance using the pandas_datareader package. The data includes the high price, low price, open price, close price, volume, and adjusted close price. The data is split into training and testing sets, and the values are scaled between 0 and 1 using the MinMaxScaler from scikit-learn.
