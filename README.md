# Stock Market Prediction using Numerical and Textual Analysis

## Objective
The goal of this project is to create a hybrid model for stock price/performance prediction. This model combines numerical analysis of historical stock prices with sentimental analysis of news headlines from that particular day.

## Approach
To achieve our objective, we follow these steps:
1. Extract Sentiment Scores from given newspaper headlines data using nltk's SentimentIntensityAnalyzer.
2. Implement Multivariate Time Series Forecasting using Keras' Long Short-Term Memory (LSTM) to model the temporal effects of past events on opening stock prices.

## Model Performance
- Training loss:0.0421
- Validation loss: 0.0293
- Root Mean Square Error (RMSE) on the Test data:560.309

## Data Sources
We used the following data for analysis and prediction:
- Historical stock prices (SENSEX - S&P BSE SENSEX) from [Yahoo Finance]
(https://finance.yahoo.com/)
- Textual (News) data from [Bitly]
(https://bit.ly/36fFPI6)

## Getting Started
1. Clone this repository to your local machine.
2. Install the required dependencies
3. Download historical stock price data and news headlines data as mentioned in the sources above.
4. Run the Jupyter Notebook or Python script for stock market prediction.

## Dependencies
- Python 3.x
- Keras
- nltk
- pandas
- numpy
- matplotlib
- scikit-learn
