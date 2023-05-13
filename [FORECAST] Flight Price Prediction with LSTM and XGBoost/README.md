# Flight Price Prediction with XGBoost and LSTM

## Introduction

This project aims to predict flight ticket prices for CGK-KUL (Cengkareng - Kuala Lumpur) and CGK-DPS (Cengkareng - Denpasar) routes. The prediction is made using XGBoost and LSTM algorithms to obtain the best time to purchase a flight ticket. The data is obtained from the Google Flights web application on November 15, 2022.

## Motivation

The use of air transportation has increased significantly, and as a result, there are many airlines with various ticket prices. Therefore, predicting the flight ticket price can help passengers to plan their trip and obtain the best ticket price. In this project, we aim to develop a model that can accurately predict flight ticket prices for CGK-KUL and CGK-DPS routes using XGBoost and LSTM algorithms.

## Methodology

The data used in this project was collected from the Google Flights web application on November 15, 2022, for the following routes: CGK-DPS, DPS-CGK, CGK-KUL, and KUL-CGK. We then preprocessed the data by cleaning, formatting, and transforming it into time series data.

Next, we developed two models, namely XGBoost and LSTM, to predict the flight ticket prices. We trained both models with the preprocessed data, and the model's performance was evaluated based on the RMSE value.

## Conclusion

The findings of this project are as follows:

1. The LSTM model is better than the XGBoost model in predicting flight ticket prices based on its RMSE value.
2. Based on the forecasting results, both models show that as the departure date approaches, flight ticket prices tend not to decrease. Therefore, the cheapest flight ticket price cannot be determined from the forecasting results for the four data points taken.
3. Based on the historical data taken, the cheapest flight ticket price cannot be determined because each route has a different time range to reach its lowest price.

This project was conducted as the final project for the Mathematical Modelling class, with a team of six members.