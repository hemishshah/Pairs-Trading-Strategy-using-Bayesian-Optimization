# Pairs Trading Strategy using Bayesian Optimization

## Overview
This project implements a **pairs trading strategy** that identifies optimal cointegrated pairs across multiple sectors and applies a **Bayesian optimization** approach to fine-tune hyperparameters for trade execution. The strategy leverages **ARIMA models** to forecast price movements and uses **backtesting** to evaluate performance, outperforming the benchmark by **30%**.

## Key Features
- **Cointegration Analysis:**
  - Identifies statistically significant pairs using the **Engle-Granger test**.
  - Applies **Johansen’s test** for multivariate cointegration verification.
  
- **Time Series Forecasting:**
  - Develops **ARIMA models** to predict price movements and residual spreads.
  
- **Hyperparameter Optimization:**
  - Optimizes **106 parameters** (buy-sell thresholds, rolling window size, etc.).
  - Uses **Bayesian optimization** (via `scikit-optimize`) to refine strategy performance.
  
- **Backtesting & Performance Evaluation:**
  - Implements a **backtest engine** to simulate real-world performance.
  - Compares results against **benchmark strategies**.
  - Achieves a **30% improvement over baseline models**.

## Data Sources
- Stock price data sourced from **Yahoo Finance** using `yfinance`.
- Sector classification retrieved from **Fama-French data**.


## Results
- The strategy was **backtested on 10 years of data**.
- Bayesian optimization significantly improved the **Sharpe ratio** and **profitability**.
- The final model outperformed traditional pairs trading approaches by **30%**.

## Next Steps
- Extend to **crypto pairs trading**.
- Implement **reinforcement learning** for adaptive trading.
- Enhance execution logic with **market microstructure analysis**.

## Author
**Hemish Shah**

---
*For detailed implementation, please check the source code in the repository.*
