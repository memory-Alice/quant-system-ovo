# Quant System V0.1

A personal quantitative equity research and backtesting system built in Python.

## Research Pipeline

Market Data → Factor Construction → IC Testing → Train/Test Validation → Multi-Factor Scoring → Portfolio Construction → Backtesting → Benchmark Comparison

## Factor Research

The system evaluates multiple quantitative signals, including:

- Momentum
- Volatility
- Volume
- Multi-Factor Score

Factor predictive power is evaluated using **Spearman Rank Information Coefficient (IC)**.

## Validation Framework

To reduce overfitting, the research period is separated into:

- **2016–2022:** Factor research / training period
- **2023–2026:** Out-of-sample-style evaluation period

## Portfolio & Backtesting

Stocks are ranked using factor signals and combined into a multi-factor portfolio.

Performance is compared against an **Equal-Weight Benchmark**.

## Performance Metrics

The system evaluates portfolio performance using:

- CAGR
- Sharpe Ratio
- Maximum Drawdown (MDD)
- Equity Curve
- Drawdown Analysis

## Notebook

The complete research workflow is available in:

`quant_system_v0_1.ipynb`

## Current Version

**V0.1**

Initial implementation of the quantitative research pipeline, factor validation framework, portfolio construction and backtesting system.

## Disclaimer

This project is for educational and research purposes only and does not constitute financial advice.
