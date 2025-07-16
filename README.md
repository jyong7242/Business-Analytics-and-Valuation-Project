# B-usiness-Analytics-and-Valuation-Project

## 📌 Overview

This project aims to construct and evaluate a stock portfolio using data-driven techniques and optimization. The strategy ranks firms based on key valuation and momentum indicators and uses historical return and risk data to build an optimal portfolio. The project combines Python-based programming with Excel validation and was completed individually as part of the MFIN602 coursework.

---

## 🎯 Objectives

- Identify undervalued and high-momentum stocks using financial ratios and return indicators
- Construct portfolios based on ranking and optimization techniques
- Evaluate portfolio performance using actual 2023 return data
- Compare optimized portfolios with equal-weighted and benchmark alternatives
---

## 💡 Methodology

### 1. Stock Ranking and Selection
Stock data from the Canadian market was ranked based on a combination of valuation (P/E, P/B, dividend yield) and momentum (cumulative return) metrics. Each firm received a composite score, and the top 10 stocks were selected for portfolio construction.

### 2. Portfolio Construction Strategies
Two strategies were developed. The first is a simple 1/N portfolio that allocates equal weights to the selected stocks. The second strategy minimizes portfolio volatility using historical standard deviation as a risk proxy. This was implemented with cvxpy under non-negativity and full-investment constraints.

### 3. Backtesting and Performance Evaluation
Daily return data from 2023 was downloaded using the Yahoo Finance API. Portfolio returns were calculated based on the constructed weights and compared to both equal-weighted portfolios and benchmark performance. Cumulative returns and Sharpe ratios were used for evaluation.

### 4. Tools and Output
The analysis was performed using Python (pandas, yfinance, cvxpy), with key results exported to Excel and PDF. Outputs include the ranked firm list, portfolio weights, return time series, and visual performance summaries.

---

## 🧰 Requirements

Install required packages with:

```bash
pip install pandas numpy matplotlib seaborn yfinance cvxpy openpyxl
```

## 🙋 Author

**Jinyan Yong**
 Master of Finance – McMaster University
