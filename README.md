# Quantity_Analysis_Time_Series_Data
Introduction

This project focuses on time series analysis and forecasting of quantity-based data using the ARIMA (AutoRegressive Integrated Moving Average) model. The objective is to analyze historical data, identify patterns (trend, seasonality, stationarity), and build predictive models to forecast future values.
Dataset

The dataset contains time-dependent quantity values recorded at regular intervals.

Preprocessing steps include handling missing values, checking stationarity, and applying transformations where necessary.

Methodology

Exploratory Data Analysis (EDA)

Visualization of trends, seasonality, and autocorrelations.

Stationarity testing (ADF Test).

Model Development

Implemented ARIMA for time series forecasting.

Optimized hyperparameters (p, d, q) using ACF, PACF plots and Grid Search.

Evaluation

Forecast accuracy measured with metrics like RMSE, MAE, and MAPE.

Comparison of predicted vs. actual values using plots.

Results

Successfully captured temporal dependencies in the dataset.

ARIMA provided accurate forecasts of future quantity values.

Visualizations demonstrated clear alignment between historical and predicted trends.

Tools & Libraries
Python

Pandas, NumPy – Data handling & preprocessing

Statsmodels – ARIMA implementation

Matplotlib, Seaborn – Data visualization
