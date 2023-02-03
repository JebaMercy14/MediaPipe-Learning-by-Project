# Time Series Model
> Time series are series of data points listed in time order.
> Time series forecasting is the use of a model to predict future values based on previously observed values.

# Problem Formulation - What are we trying to solve?
> We want to forecast the GDP per Capita per country for the next 7 to 10 years

# ARIMA:

Uses a number of lagged observations of time series to forecast observations
Inputs / Parameters:

- p: the number of lag observations in the model; also known as the lag order (AR)
- d: the number of times that the raw observations are differenced; also known as the degree of differencing (I)
- q: the size of the moving average window; also known as the order of the moving average (MA)

# Prophet

> Prophet is open source software released by Facebook’s Core Data Science team
> Prophet is a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality
> It works best with time series that have strong seasonal effects and several seasons of historical data.
> Prophet is robust to missing data and shifts in the trend, and typically handles outliers well.
