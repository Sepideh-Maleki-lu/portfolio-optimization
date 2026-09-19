# Portfolio Optimization with Practical Constraints and Backtesting

This project was completed as part of the Master in Financial Mathematics
program at the University of Luxembourg.

The objective is to study portfolio optimization using real financial data
and to examine how practical constraints affect portfolio diversification,
risk, and out-of-sample performance.

## Data

The analysis uses daily prices for 10 large-cap US stocks:

AAPL, BAC, GOOG, GS, LLY, META, MRK, TSLA, WMT, and XOM.

- Modeling period: January 2019 – December 2024
- Backtesting period: January 2025
- Data source: Yahoo Finance

## Methods

The project includes:

- Mean-variance portfolio optimization
- No-short-selling constraints
- Box constraints on individual asset weights
- Unconstrained mean-variance optimization
- Turnover constraints
- Portfolio concentration analysis using the Herfindahl-Hirschman Index (HHI)
- Efficient frontier comparison
- Out-of-sample portfolio backtesting
- Comparison with an equal-weight benchmark

## Tools

- Python
- NumPy
- Pandas
- Matplotlib
- CVXPY
- yfinance

## Main Findings

The basic mean-variance portfolio can produce highly concentrated or
extreme allocations.

Adding practical constraints improves diversification and produces more
realistic portfolio allocations.

In the out-of-sample backtest, the box-constrained portfolio showed more
stable behavior than the basic no-short-selling mean-variance portfolio.

The equal-weight portfolio was also used as a benchmark to evaluate the
optimized portfolios.

## Files

- `Portfolio_Optimization_Sepideh_Maleki Roudposhti.ipynb` – Python implementation and analysis
- `portfolio_optimization_report.pdf` – Full project report

## Author

Sepideh Maleki-Roudposhti

University of Luxembourg  
Master in Financial Mathematics
