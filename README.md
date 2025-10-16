📈 IHSG Prediction using Machine Learning (2020–2025 Data)

📘 Overview

This project focuses on forecasting the Indonesia Composite Index (IHSG) using historical data from 2020 to 2025.
The goal is to predict future price trends — including 30-day ahead and one-year ahead forecasts — to better understand market behavior and assist in investment or risk management decision-making.
The project integrates year-over-year analysis (YoY) to ensure data consistency and improve long-term forecasting accuracy.

🎯 Objectives

• Predict IHSG movement for the next 30 days and next year.

• Perform year-over-year integration to stabilize data and capture seasonal patterns.

• Compare multiple machine learning models to identify the best-performing algorithm for time-series forecasting.

• Visualize and evaluate the model’s performance using various metrics.

🧠 Machine Learning Methods

Several ML algorithms were explored and tested to identify which model produces the most accurate predictions.
The main approaches include:

• Linear Regression — as a baseline model.

• Random Forest Regressor — to capture nonlinear relationships.

• XGBoost / LightGBM — for gradient boosting–based forecasting.

• LSTM (Long Short-Term Memory) — for deep learning–based time series prediction (optional advanced part).

Each model was tuned and compared using metrics such as RMSE, MAE, and R² Score.

📊 Data Description

Source: IHSG daily historical data from 2020 to 2025 (e.g., Yahoo Finance, IDX, or Kaggle).
Frequency: Daily closing prices.

Features Used:

• Date

• Open, High, Low, Close prices

• Volume

• Year-over-Year returns (YoY)

• Moving averages (MA7, MA30, MA90)

• Lag features for previous N days

• All data were cleaned, normalized, and split into training and testing sets for model evaluation.

⚙️ Project Workflow

• Data Collection & Cleaning — remove missing values, handle outliers, and ensure time continuity.

• Feature Engineering — generate lag features, moving averages, and YoY ratios.

• Exploratory Data Analysis (EDA) — visualize IHSG trends, volatility, and seasonality patterns.

• Model Training — train and tune multiple ML models.

• Model Evaluation — evaluate performance using RMSE, MAE, and R².

• Forecasting — generate predictions for the next 30 days and next year.

• Visualization — plot actual vs predicted values and confidence intervals.

📈 Results

• The Random Forest and XGBoost models produced the best overall performance for mid-term predictions.

• The LSTM model performed well in capturing longer-term patterns, especially for one-year forecasts.

• Incorporating year-over-year data integration improved stability and reduced overfitting.

Example output visualization includes:

• Actual vs Predicted IHSG values

• 30-day and 1-year forecast charts

• Feature importance plots

💡 Insights

• IHSG shows strong seasonal trends and momentum effects across years.

• Year-over-year integration enhanced prediction smoothness and reduced short-term noise.

• Combining ML and time-series techniques provides both interpretability and forecasting power.

🧰 Tech Stack

• Programming Language: Python

• Libraries:

  • pandas, numpy
  
  • scikit-learn
  
  • xgboost, lightgbm
  
  • matplotlib, seaborn
  
  • tensorflow / keras (for LSTM)
  
• Environment: Jupyter Notebook / Google Colab








