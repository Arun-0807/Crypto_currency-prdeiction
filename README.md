# Cryptocurrency Closing Price Prediction Using LSTM

## Overview
This project predicts the next day's cryptocurrency closing price using historical market data and an LSTM deep learning model in Google Colab.

## Technologies Used
- Python
- Google Colab
- Pandas and NumPy
- Scikit-learn
- TensorFlow/Keras
- Matplotlib

## Features
- Load cryptocurrency data from Kaggle.
- Handle missing values and normalize numerical features.
- Create 7-day sliding-window sequences.
- Train an LSTM model to predict closing prices.
- Evaluate the model using MAE and RMSE.
- Plot actual versus predicted closing prices.

## Dataset
The dataset is downloaded from Kaggle and contains historical cryptocurrency market data. Approximately 2,000 consecutive daily records are used.

## How to Run
1. Open the project notebook in Google Colab.
2. Upload your cryptocurrency CSV dataset.
3. Run the code cells in order.
4. View the evaluation metrics, graphs, and predicted closing prices.

## Model
An LSTM (Long Short-Term Memory) neural network is used to learn patterns from the previous 7 days of market data and predict the next day's closing price.

## Evaluation Metrics
- **MAE:** Mean Absolute Error
- **RMSE:** Root Mean Squared Error

## Disclaimer
This project is intended for educational purposes only. Cryptocurrency price predictions are uncertain and should not be considered financial advice.
