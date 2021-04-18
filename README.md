# Revenure-Forecasting

A revenue forecast is an estimate of your revenues over a fixed period of time. To understand thoroughly how sales channels work and how prospects become customers. On a high level, many companies develop sales forecasts by applying an expected or desired market growth rate to current year revenues. These forecasts are then substantiated using a bottom-up forecasting approach that takes into account inputs such as projected product units sold, price, sales productivity and seasonality, to name a few.

Here, I have used time series forecasting to predict future sales. Time series analysis comprises methods for analyzing time series data in order to extract meaningful statistics and other characteristics of the data. Time series forecasting is the use of a model to predict future values based on previously observed values. This will cover few terminologies - 

## 1. Augmented Dickey-Fuller test
The Augmented Dickey-Fuller test is a type of statistical test called a unit root test.
The intuition behind a unit root test is that it determines how strongly a time series is defined by a trend. It uses
an autoregressive model and optimizes an information criterion across multiple different lag values.
The null hypothesis of the test is that the time series can be represented by a unit root, that it is not stationary
The null hypothesis of the test is that the time series can be represented by a unit root, that it is not stationary

## 2. Differencing in Time Series Data
Differencing is a method of transforming a time series dataset.
It can be used to remove the series dependence on time, so-called temporal dependence. This includes
structures like trends and seasonality. Differencing is performed by subtracting the previous observation from
the current observation.

## 3. Lag Difference
Taking the difference between consecutive observations is called a lag-1 difference.
The lag difference can be adjusted to suit the specific temporal structure.
For time series with a seasonal component, the lag may be expected to be the period (width) of the seasonality.

## 4. SARIMA Model
Seasonal Autoregressive Integrated Moving Average, SARIMA or Seasonal ARIMA, is an extension of ARIMA
that explicitly supports univariate time series data with a seasonal component.
It adds three new hyperparameters to specify the autoregression (AR), differencing (I) and moving average (MA)
for the seasonal component of the series, as well as an additional parameter for the period of the seasonality.

## 5. ARIMA Model
ARIMA, short for ‘Auto Regressive Integrated Moving Average’ is actually a class of models that ‘explains’ a
given time series based on its own past values, that is, its own lags and the lagged forecast errors, so that
equation can be used to forecast future values.
Any ‘non-seasonal’ time series that exhibits patterns and is not a random white noise can be modeled with
ARIMA models.
