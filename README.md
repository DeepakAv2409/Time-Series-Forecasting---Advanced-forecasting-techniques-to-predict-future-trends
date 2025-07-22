# 📊 Time-Series-Forecasting

Forecasting 12-month sales using ARIMA, SARIMA, exponential smoothing, and moving averages on two real-world datasets.  
Includes model evaluation, RMSE comparison, and forecast visualizations with confidence intervals.

---

## 📁 Project Overview

This repository contains two real-world forecasting projects using statistical and machine learning models:
- **Shoe Sales Forecasting** for IJK Shoe Company
- **Soft Drink Sales Forecasting** for a beverage brand  
*(Sales data from 1980 to 1995)*

🎯 **Goal:** Predict the next 12 months of sales and recommend the most accurate predictive model.

---

## 🛠️ Techniques Used

- **Data Cleaning & Transformation**
- **Time Series Decomposition** (Additive & Multiplicative)
- **Stationarity Testing** (ADF Test)
- **Forecasting Models:**
  - Linear Regression
  - Naive & Average Models
  - Moving Averages (4, 6, 9 points)
  - Exponential Smoothing (Simple, Double, Additive, Multiplicative)
  - ARIMA & SARIMA (Manual and Auto)

---

## 📈 Results

### 🥿 Project 1: Shoe Sales
- **Best Model:** `Manual SARIMA (2,1,1)(1,0,3,12)`
- **RMSE:** `47.87`

### 🥤 Project 2: Soft Drink Sales
- **Best Model:** `Exponential Smoothing (Multiplicative)`
- **RMSE:** `447.62`

---

## 📌 Key Takeaways
- Compared multiple models using RMSE to select optimal forecasting strategy
- Used stationarity transformation and decomposition for robust time series analysis
- Final forecasts include confidence intervals for better risk assessment

---

