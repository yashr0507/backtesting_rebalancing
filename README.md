# Portfolio Backtesting and Rebalancing Strategy Analysis

A Python-based quantitative finance project that backtests optimized and equal-weight portfolios while evaluating the impact of periodic portfolio rebalancing on long-term performance using historical market data.

## Overview

Portfolio optimization identifies an ideal asset allocation, but portfolio weights naturally drift over time as individual assets generate different returns. This project simulates periodic portfolio rebalancing by resetting portfolio weights back to their optimized allocation on a monthly and quarterly basis.

The project compares optimized, equal-weight, monthly rebalanced, quarterly rebalanced, and S&P 500 benchmark portfolios using multiple risk-adjusted performance metrics over five years of historical market data.

## Assets Used

* Apple (AAPL)
* Microsoft (MSFT)
* NVIDIA (NVDA)
* Coca-Cola (KO)
* Gold Futures (GC=F)
* S&P 500 Index (^GSPC)

## Features

* Historical market data collection using yfinance
* Equal-weight portfolio construction
* Optimized portfolio backtesting
* Monthly portfolio rebalancing simulation
* Quarterly portfolio rebalancing simulation
* Wealth index calculation
* CAGR calculation
* Rolling annualized volatility analysis
* Rolling Sharpe ratio analysis
* Maximum drawdown analysis
* Performance comparison across five investment strategies
* Automated summary table generation and CSV export

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* yfinance

## Visualizations

The project generates:

* Portfolio Wealth Index Comparison
* Rolling Annualized Volatility Comparison
* Rolling Sharpe Ratio Comparison
* Wealth Index and Drawdown Analysis
* Performance Summary Table

## Key Concepts

* Portfolio Backtesting
* Portfolio Rebalancing
* Portfolio Drift
* Equal-Weight Investing
* Portfolio Optimization
* Compound Annual Growth Rate (CAGR)
* Wealth Index
* Rolling Volatility
* Sharpe Ratio
* Maximum Drawdown
* Risk-Adjusted Performance
* Benchmark Comparison

## Future Improvements

* Transaction cost and slippage modelling
* Risk-free rate adjusted Sharpe ratio
* Dynamic rebalancing based on drift thresholds
* Calendar vs threshold-based rebalancing comparison
* Walk-forward optimization
* Interactive dashboards using Plotly or Dash
