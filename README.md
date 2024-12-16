# AutoMarket-Trading-Insights
## Objective
The main objective of this project is to develop a robust and accurate model for
predicting the future stock prices of Tesla, BMW, Volkswagen, Hyundai, andFord. By utilizing historical data from 2019 to 2024 collected from Yahoo Finance, weaim to compare the performance of Long Short-Term Memory (LSTM) andGatedRecurrent Unit (GRU) models. The ultimate goal is to implement an interactiveinterface using Streamlit, where users can input the number of days in the futurefor which they wish to predict stock prices, and obtain precise forecasts. 
##  Methodology
1. Data Collection: Historical stock price data for Tesla, BMW, Volkswagen, Hyundai, and Ford from 2019 to 2024 were collected from Yahoo Finance.
2. 2. Data Preprocessing: The data was cleaned, normalized, and split into trainingand testing sets to ensure the model's score.
3. 3. Model Development:
 LSTM Model: A model based on Long Short-Term Memory (LSTM) networkswas developed to capture the temporal dependencies in the data.
 GRU Model: A Gated Recurrent Unit (GRU) model was also developed andcompared against the LSTM model.
 3. Model Evaluation: The models were evaluated based on their predictionRMSE, with the GRU model showing superior performance.
