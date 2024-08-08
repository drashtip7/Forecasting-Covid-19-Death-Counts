# Forecasting-Covid-19-Death-Counts

Here we will be  working with a dataset containing daily Covid-19 death counts for each U.S. state, sourced from the John Hopkins University Center for Systems Science and Engineering. This dataset aggregates daily Covid-19 cases from April 12, 2020, to March 26, 2022.

Here's how you can approach the assignment:

## 1)Dataset Overview:

Data Source: covid_19_daily_reports_us.csv
Date Range: April 12, 2020 – March 26, 2022


The task is to train deep learning models to forecast the moving average of daily Covid-19 death counts for each state.
Forecasting Horizon: 1 month into the future.
Historical Data Window: Past 60 days.
Steps to Complete the Assignment:

## 2)Data Preparation:

Download and read the dataset using the wget command in Colab or other methods for handling CSV files.
Clean and preprocess the data, ensuring it’s in a suitable format for modeling.
Calculate the moving average of daily death counts based on the past 60 days of data.

## 3)Feature Engineering:

Generate features that could help the model capture temporal patterns, such as time lags, rolling statistics, and trend indicators.

## 4)Model Development:

Select and train appropriate deep learning models for time series forecasting, such as LSTM (Long Short-Term Memory) networks or GRUs (Gated Recurrent Units).
Tune the model parameters to optimize performance.

## 5)Evaluation:

Evaluate the model’s forecasting accuracy using metrics such as MAE (Mean Absolute Error) or RMSE (Root Mean Squared Error).
Validate the model on a test set or through cross-validation.

