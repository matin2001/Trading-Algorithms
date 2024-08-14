# ARIMA-GARCH-Strategy-for-Cryptocurrency-Forecasting

This project implements a trading strategy using ARIMA and GARCH models to predict cryptocurrency price movements. The workflow includes:

Data Collection: Gathered daily historical data for Bitcoin and Ethereum from July 1, 2021, to July 1, 2023, using it for training and testing.

Model Implementation: Applied the ARIMA model to forecast future values, optimized based on AIC criteria. Used GARCH to estimate volatility of ARIMA residuals, and generated buy/sell signals based on predicted mean values.

Rolling Window Analysis: Employed rolling windows to optimize ARIMA parameters and trained ARCH models. Saved generated signals in a CSV file.

Backtesting and Evaluation: Developed a backtesting function to simulate trading with an initial investment of $100. Calculated performance metrics such as MSE, MAPE, and Sharpe Ratio. Plotted equity curves for ARIMA-GARCH and Buy & Hold strategies for comparison.
