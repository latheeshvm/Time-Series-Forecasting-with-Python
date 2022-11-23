# Anatomy of forecasting product

### Traditional approach was <br>

- Model -----> Outcome
- Forcasting Model -------> Forecast

### Modern Forecasting Product <br>

- Model 1
- Model 2 ---> Ensemble( A collection of things that intended to be used together) --> `Forecast`
- Model 3

### Why Ensemble ( combine forecast models to get a better forecast)

### Why forecast matters

- Understand financial consequences
- `Gross Sales before cancellation` | `Cancellation Rate Value` | `Return Rate Value` || `=>` Net Merchandise Volume

### What is time series data

= Sequence of data points in time order recorded in equally distanced time period

- Trend
- Seasonality
- Error

### Case Study

- Airbnb missed the earning expectations
- Airbnb struggling in the US market

Forcasting Product

- Demand in Newyork

What data we have

1. Holidays, Temperature and Marketing Investment
2. Daily Demand($)
3. Historical Data to find patterns
4. Predict demand of the incoming month

### Additive vs Multiplicative Seasonality

if we are considering the seasonality in terms of percentage, then we should consider multiplicative seasonality
if we are dealing with absolute values then it's additive

Additive `Trend + Seasonality + Error` <br>
<img src="https://latex.codecogs.com/png.latex?\color{white} y[t] = Tt[t] + S[t] + e[t] " /> <br>

Multiplicative `Trend * Seasonality * Error` <br>
<img src="https://latex.codecogs.com/png.latex?\color{white} y[t] = Tt[t] * S[t] * e[t] " />

Auto- Correlation plorts (ACF)

- A check to see if there is information in the past to make a decision
- correlation with past
- Slope - Linear regression for a year

DataAnalysis : DataAnalysis.ipynb
