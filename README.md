# 🔮 Forecasting BBCA Stocks Market 💰 Using Prophet

![BBCA Stocks Market Forecasting](https://github.com/ARKnajmi/StockForecast/assets/149140186/25af6952-f9b6-4596-a174-5648c39d90e7)

## 📋 Table of Contents
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Features](#features)
- [Prior Knowledge](#prior-knowledge)
- [EDA (Exploratory Data Analysis)](#eda-exploratory-data-analysis)
- [Data Preprocessing](#data-preprocessing)
- [Modeling with Prophet](#modeling-with-prophet)
- [Model Evaluation](#model-evaluation)
- [Conclusion](#conclusion)
- [Usage](#usage)

## ⭐ Introduction
This project aims to forecast the stock market of Bank Central Asia (BBCA) using the Prophet forecasting model. The project involves data analysis, visualization, data preprocessing, modeling with Prophet, and model evaluation to predict future stock prices accurately.

## 🔎 Project Overview
The project utilizes historical stock market data of BBCA from June 08, 2004, to December 01, 2023, obtained through the Yahoo Finance API. The data includes features such as Open, High, Low, Close, Volume, Dividends, and Stock Splits.

## 🧾 Libraries Used

The project utilizes several libraries for data manipulation, visualization, modeling, and evaluation:

- [yfinance](https://pypi.org/project/yfinance/): A library for downloading historical market data from Yahoo! Finance.
- [pandas](https://pandas.pydata.org/): A powerful data manipulation and analysis library.
- [plotly](https://plotly.com/python/): An interactive visualization library for creating charts and graphs.
- [Prophet](https://facebook.github.io/prophet/): A forecasting model developed by Facebook's Core Data Science team, specifically designed for time series forecasting tasks.
- [scikit-learn](https://scikit-learn.org/): A machine learning library for model validation and evaluation.

These libraries are essential for pulling stock market data, performing exploratory data analysis, visualizing trends, modeling time series data, and evaluating model accuracy.


## ✨ Features
- **Data Importing and Visualization**: Importing stock market data using yfinance and visualizing it using Plotly to understand trends and patterns.
- **Exploratory Data Analysis (EDA)**: Analyzing data distribution, visualizing trends over time, and understanding key features.
- **Data Preprocessing**: Preprocessing data by resetting the index, selecting relevant columns, and converting date formats.
- **Modeling with Prophet**: Fitting the Prophet model to training data, making future predictions, and evaluating forecasted values.
- **Model Evaluation**: Evaluating the model's performance using Mean Absolute Percentage Error (MAPE) to assess accuracy.

## 💡 Prior Knowledge
Before diving into the project, it's essential to understand the meaning of stock market features like Open, High, Low, Close, Volume, Dividends, and Stock Splits. These features play a crucial role in analyzing and predicting stock market trends.

## 📈 EDA (Exploratory Data Analysis)
EDA involves visualizing data using heatmaps, line charts, and candlestick plots to analyze patterns, trends, and anomalies in the stock market data.

## ⚙️ Data Preprocessing
Data preprocessing includes resetting the index, selecting relevant columns, converting date formats, and preparing the data for modeling with Prophet.

## 💻 Modeling with Prophet
Prophet is a forecasting model developed by Facebook's Core Data Science team, specifically designed for time series forecasting tasks. It involves fitting the model to training data, making future predictions, and visualizing forecasted values.

## ⚖️ Model Evaluation
Model evaluation involves assessing the accuracy of the forecasted values using Mean Absolute Percentage Error (MAPE) to determine the model's performance.

## 🏁 Conclusion
![image](https://github.com/ARKnajmi/StockForecast/assets/149140186/a69c5e07-b81f-41bb-8e33-e35287f71dc4)

The project concludes with a highly accurate forecasting model for BBCA stock prices, achieving a MAPE value of 8.3%. This demonstrates the effectiveness of using Prophet for stock market forecasting.

## 🗝️ Usage
To use this project:
1. Clone the repository to your local machine.
2. Install the required libnrary/dependencies.
3. Run the Jupyter Notebook or Python script to analyze and forecast BBCA stock prices.
