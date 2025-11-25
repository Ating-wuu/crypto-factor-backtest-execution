# Crypto Factor Backtesting & Binance Paper Trading System (Individual Contribution)

This repository only contains the core modules that I implemented for a crypto trading system that runs factor-based backtests and executes paper trading on the Binance Futures Testnet.

Key components I developed:
- **Trading factors**: Bias, CCI, Momentum Mean, PctChange, QuoteVolumeMean  
- **Backtesting performance engine**: annual return, max drawdown, win-rate, Sharpe (see `evaluate.py`)
- **Execution logic**: TWAP order splitting with exchange precision handling (`split_order.py`)
- **Numba-accelerated simulator** for multi-asset execution (`simulator.py`)
- **Live monitoring**: margin-rate & drawdown circuit breakers, auto-reduce-position logic (`monitor.py`)
- **Notification system** using WeChat Work API (`notification.py`)

This subset contains only my individual work; the full project remains private due to academic policy.
