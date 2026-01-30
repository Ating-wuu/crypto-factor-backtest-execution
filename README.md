# Crypto Factor Backtesting & Binance Paper Trading System (Individual Contribution)

The project focuses on building a general research and backtesting framework using a wide range of technical indicators.
The primary goal is to explore the research process and robustness testing, rather than to present a single production-ready trading strategy.

This repository contains only the core modules I implemented for this project, which run factor-based backtests and execute paper trading on the Binance Futures Testnet.

Key components I developed:
- **Trading factors**: Bias, CCI, Momentum Mean, PctChange, QuoteVolumeMean  
- **Backtesting performance engine**: annual return, max drawdown, win-rate, Sharpe (see `evaluate.py`)
- **Execution logic**: TWAP order splitting with exchange precision handling (`split_order.py`)
- **Numba-accelerated simulator** for multi-asset execution (`simulator.py`)
- **Live monitoring**: margin-rate & drawdown circuit breakers, auto-reduce-position logic (`monitor.py`)
- **Notification system** using WeChat Work API (`notification.py`)

This subset contains only my individual work; the full project remains private due to academic policy.
