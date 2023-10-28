# Task-1-Stock-Prediction
Stock Prediction
Bharat Data Science Intern
Take stock price of any company you want and predicts its price by using LSTM.

Stock Price Prediction using LSTM
This project demonstrates how to use Long Short-Term Memory (LSTM) neural networks to predict stock prices. By utilizing the power of LSTM, we can capture temporal dependencies and make accurate predictions based on historical data.

The project is implemented in a Jupyter Notebook and follows the following steps:

Data Collection: The stock price data is loaded from a CSV file, which contains the historical prices.
Data Preprocessing: The relevant columns are selected, the 'Date' column is converted to datetime format, and the data is scaled using MinMaxScaler to ensure consistent ranges.
Data Split: The preprocessed data is split into training and testing sets, with a specified ratio.
LSTM Model Creation: An LSTM model is built using the TensorFlow library. It consists of LSTM layers to capture temporal patterns and a dense output layer for prediction.
Model Training: The LSTM model is trained on the training data, specifying the number of epochs, batch size, and validation split.
Prediction and Evaluation: The trained model is used to make predictions on the test data. The predictions and actual values are inverse transformed to their original scales, and the root mean squared error (RMSE) is calculated to evaluate the model's performance.
Visualization: The predicted and actual values are plotted to provide a visual representation of the model's predictions.
This project serves as a starting point for predicting stock prices using LSTM. By experimenting with different parameters, techniques, and data sources, you can further enhance the accuracy of the predictions.

Data Source: Yahoo BTC/USD CSV File
The stock price data used in this project is sourced from the Yahoo Finance API. Specifically, the BTC/USD (Bitcoin to US Dollar) historical data is obtained from a CSV file provided by Yahoo.

Name :- vemulamada sai vikas
Email :- vemulamadasaivikas@gmail.com
Contact :- 6301917312
