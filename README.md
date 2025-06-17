# Project for the Statistical Models for Data Science Course of UNIVR

This project focuses on the analysis and forecasting of daily wind power generation in Germany between 2017 and 2019. 
The goal is to build a complete time series forecasting pipeline and predict wind energy production for December 2019 using different statistical models.

## 📊 Dataset

The dataset contains daily observations with the following variables:
- `wind_generation`: Wind energy production (in MWh)
- `wind_capacity`: Installed wind capacity (in MW)
- `temperature`: Average daily temperature (in °C)

## 📈 Project Objectives

- Explore and visualize time series characteristics
- Check for trends, seasonality, and stationarity
- Apply seasonal and log-transformations where needed
- Compare simple forecasting methods (mean, naïve, seasonal naïve, drift)
- Implement Exponential Smoothing models (ETS additive and multiplicative)
- Build and tune SARIMA/SARIMAX models for improved forecasting
- Evaluate models using metrics such as RMSE, MAE, MAPE, AIC
