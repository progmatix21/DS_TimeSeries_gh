# Time Series Analysis and Prediction using Auto ARIMA

ARIMA stands for Auto Regression Integrated Moving Average. It is parameterized by the hyperparameters p, d and q where:

- p is the number of autoregressive terms.
- d is the order of differencing to make the series stationary.
- q is the number of moving average error terms.

We use Microsoft stock price to train our model and use it to predict the trend as well as compare it with the test split of the series. 

## Sequence of steps

1. Check for stationarity using Augmented Dickey-Fuller test.
2. Plot ACF and PACF to get a feel for the hyperparameter p.
3. Decompose the signal to study the periodicity or the number of observations per cycle.
4. Build the model using Auto ARIMA which uses grid search to arrive at the best values of p,d and q.
5. Predict and plot the series.

