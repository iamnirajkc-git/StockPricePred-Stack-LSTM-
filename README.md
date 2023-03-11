# StockPricePred-Stack-LSTM-

# Stock Price Prediction Using Stacked LSTM
This project demonstrates how to use stacked LSTM to predict the stock price of a company for the next 30 days. We use historical stock price data obtained from Tiingo using the pandas_datareader library.

# Prerequisites
Before running the code, make sure you have the following installed:

Python 3.6 or later
Pandas
Pandas Datareader
Tensorflow
Scikit-learn
You can install the required packages using pip as follows:

bash
Copy code
pip install pandas pandas-datareader tensorflow scikit-learn

# Usage
To use this code, follow these steps:


Obtain a Tiingo API key by creating an account at Tiingo.
Replace the TIINGO_API_KEY variable in the get_data.py file with your Tiingo API key.
Run the get_data.py script to download the historical stock price data and save it to a CSV file.
Run the train_model.py script to train the stacked LSTM model using the downloaded data and save the model to a file.
Run the predict.py script to generate predictions for the next 30 days using the trained model and plot the results.

# Acknowledgments
This project was inspired by [this](https://www.youtube.com/watch?v=H6du_pfuznE&t=173s&ab_channel=KrishNaik) blog post.
The Tiingo API was used to obtain the historical stock price data.




