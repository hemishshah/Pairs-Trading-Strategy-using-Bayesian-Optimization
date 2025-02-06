

---

# Optimized Algorithmic Pairs Trading

## Project Overview

This project implements an optimized algorithmic trading strategy based on **pairs trading**. The strategy involves identifying cointegrated pairs of stocks, forecasting price movements using ARIMA models, and optimizing trading parameters using Bayesian optimization. The strategy is backtested and compared to a benchmark to evaluate its performance.

### Key Features:
- **Cointegration Analysis**: Identifying cointegrated pairs of stocks.
- **ARIMA Forecasting**: Using ARIMA models to predict stock prices.
- **Bayesian Optimization**: Optimizing trading parameters for better performance.
- **Backtesting**: Testing the strategy on historical data and comparing it to a benchmark.

## Files in This Repository:
- **experiment.ipynb**: Core experiments including data collection, cointegration testing, model training, optimization, and backtesting.
- **new_test.ipynb**: Additional tests and analyses.
- **src/**: Source code for utilities, models, and optimization.



## Usage

1. **Data Collection**: Download stock price data using Yahoo Finance.
2. **Cointegration Test**: Identify cointegrated pairs using the `cointegration_test()` function.
3. **ARIMA Forecasting**: Train an ARIMA model on selected pairs.
4. **Optimization**: Use **Bayesian Optimization** to fine-tune strategy parameters.
5. **Backtest**: Evaluate the strategy’s performance with the `backtest_strategy()` function.

## Performance Metrics
- **ROI**: Return on investment.
- **Sharpe Ratio**: Risk-adjusted return.
- **Max Drawdown**: Largest peak-to-trough decline.
- **Benchmark Comparison**: Performance relative to a market index (e.g., S&P 500).

## Conclusion
This project optimizes a pairs trading strategy using statistical methods and machine learning to achieve superior performance in the financial market.

