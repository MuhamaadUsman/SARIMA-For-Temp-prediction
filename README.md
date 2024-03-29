# SARIMA Temperature Prediction Model

This repository contains a Python implementation of a seasonal autoregressive integrated moving average (SARIMA) model for temperature prediction. The SARIMA model is a popular time series forecasting technique that is commonly used to analyze data that exhibits seasonal trends and patterns. In this implementation, we use the SARIMA model to predict future temperatures based on historical temperature data.

## Data The data used in this implementation is included in the repository in the file temperature.csv. The data consists of temperature measurements taken at regular intervals over a period of several years. We will use this data to train the SARIMA model and to make temperature predictions.

## Time Series Stationarity Before we can apply the SARIMA model, we must first ensure that our time series is stationary. Stationarity is an important assumption of the SARIMA model, as it requires that the statistical properties of the time series remain constant over time. In this implementation, we check for stationarity using the Augmented Dickey-Fuller (ADF) test, which tests for the presence of a unit root in the time series.

If the time series is not stationary, we can make it stationary by removing trends and seasonal components. Trends are long-term changes in the time series, while seasonal components are recurring patterns that occur over a fixed time period. We can remove these components by taking first differences or seasonal differences, respectively.

## Implementation The implementation consists of a Jupyter notebook SARIMA_Temperature_Prediction.ipynb, which contains the code for training and evaluating the SARIMA model. The notebook is organized as follows:

Importing libraries and loading the data Exploratory data analysis (EDA) to understand the data Time series stationary check using the ADF test Making the time series stationary by taking first and seasonal differences Splitting the data into training and testing sets Fitting the SARIMA model on the training data Evaluating the performance of the model on the testing data Visualizing the predictions and comparing them to the actual values To run the code, simply open the Jupyter notebook SARIMA_Temperature_Prediction.ipynb and follow the instructions provided in the notebook. The notebook contains detailed explanations of the code and the output of each cell, which should help you to understand the implementation and how to use it for temperature prediction.

# Conclusion In conclusion, this implementation demonstrates how to use the SARIMA model for temperature prediction, and how to check for time series stationarity using the ADF test. By removing trends and seasonal components, we can make our time series stationary, which allows us to apply the SARIMA model and make accurate temperature predictions.
