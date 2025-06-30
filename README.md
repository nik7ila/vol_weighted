# vol_weighted
# Volatility-Weighted Portfolio Strategy
This project constructs and evaluates a volatility-weighted portfolio using four assets: AAPL, TSLA, AMZN, and DIS, and compares it against the Markowitz Mean-Variance Optimized (MVO) portfolio and the S&P 500 benchmark (2015–2025).

# Purpose
To understand and implement risk-based portfolio construction—specifically volatility weighting—and contrast its outcomes with classic optimization (MVO). The goal is to simulate how investment strategies may perform under different assumptions about risk, return, and diversification.

# Approach
- Used AI-assisted learning to break down academic concepts like Mean-Variance Optimization and volatility targeting.

- Wrote code with support to automate data loading, risk estimation, and backtesting.

- Compared all portfolio strategies using clear visual and statistical benchmarks.

# Methodology
1. Data & Setup
Tickers: AAPL, TSLA, AMZN, DIS

Period: 2015-01-01 to 2025-01-01

Libraries: yfinance, numpy, pandas, matplotlib, scipy

2. Portfolio Construction
# Strategy	Description
Volatility-Weighted	Weights inversely proportional to historical volatility. Lower-risk assets get more allocation.
MVO Portfolio	Maximizes Sharpe Ratio using Markowitz optimization (via scipy.optimize).
Benchmark (S&P 500)	Proxy using SPY data for passive investment comparison.

3. Backtest & Comparison
Portfolio daily returns

Cumulative growth

Sharpe & Sortino Ratios

Visual comparison across all strategies

# Key Learnings
Volatility-weighted portfolios offer intuitive risk control without requiring return forecasts.

MVO portfolios, while optimal on paper, are sensitive to estimation error.

Using AI-assisted guidance made it easier to grasp complex financial math, structure clean notebooks, and produce consultant-ready insights.

Visual comparisons & benchmarking improve interpretability for decision-makers.

# Results Preview

Comparison of cumulative returns for all three strategies.

# Dependencies
bash
Copy
Edit
pip install yfinance numpy pandas matplotlib scipy
