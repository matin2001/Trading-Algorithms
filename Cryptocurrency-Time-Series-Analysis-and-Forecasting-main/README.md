# Cryptocurrency-Time-Series-Analysis-and-Forecasting

This project involves a comprehensive analysis of historical cryptocurrency data from Yahoo Finance. It includes:

Stationarity Test: Collected historical data for the top five cryptocurrencies (by market cap) across three timeframes (daily, 4-hour, and 1-hour) from November 1, 2022, to November 1, 2023. Applied the ADF test to determine stationarity, identified the most stationary series, and plotted its price chart. If none were stationary, lower market cap cryptocurrencies were evaluated.

Parameter Estimation: For the stationary series, used ACF and PACF plots to determine appropriate parameters for AR, MA, and ARMA models. Trained the models on 11 months of data and tested on the remaining month, evaluating them with Mean Absolute Percentage Error (MAPE) and Mean Squared Error (MSE).

Optimization: Employed brute-force search to find optimal p and q values for AR, MA, and ARMA models within a range of 1 to 50. Compared these optimized parameters with those obtained from ACF and PACF plots.
