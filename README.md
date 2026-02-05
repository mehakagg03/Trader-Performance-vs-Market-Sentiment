# Trader-Performance-vs-Market-Sentiment

## 📊 Project Overview
This project analyzes the relationship between market sentiment (measured by the Fear & Greed Index) and trader performance metrics. By segmenting data into psychological regimes (Fear, Neutral, and Greed), we identify how shifts in market emotion influence profitability, risk-taking, and trading frequency.

### Objectives
- Performance Benchmarking: Compare PnL and Win Rates across different sentiment phases.

- Behavioral Mapping: Determine if traders increase leverage or trade frequency based on sentiment.

- Risk Segmentation: Identify high-risk trader profiles (e.g., High Leverage vs. Low Leverage).

### Setup
1. Install requirements: `pip install pandas numpy`
2. Ensure your data matches the schema provided in the prompt.

### How to Run
Run the script via terminal:
Market segmentation vs Trader performance.ipynb

Here is a comprehensive README.md for your project. This document structures the analysis of market sentiment (Fear & Greed) against trading performance, providing a clear guide for anyone looking to run the script or understand the findings.

Sentiment-Driven Trader Performance Analysis

## 📈 Methodology
The analysis follows a three-step segmentation process:

Regime Classification:

- Fear: Fear & Greed Index < 45

- Neutral: Fear & Greed Index 45–55

- Greed: Fear & Greed Index > 55

Performance Metrics: Calculation of average Daily PnL, Win Rates, and Drawdown Proxies (average loss on negative days).

Behavioral Metrics: Evaluation of average leverage and trade counts to detect overtrading or over-leveraging.

## 💡 Key Insights & Strategies
Insights
- The Greed Trap: While total PnL is highest during Greed phases, the "loss severity" (drawdown) is significantly higher, indicating traders take on asymmetric risk.

- The Leverage Penalty: High-leverage segments consistently underperform across all regimes compared to low-leverage segments.

- Activity Surge: Trade frequency doubles during Greed phases, often leading to diminished returns due to fees and slippage.

## Strategy Recommendations
- Defensive Pivot: Reduce account-wide leverage by 50% when the index drops into "Fear" territory.

- Frequency Cap: Implement a daily trade limit during "Extreme Greed" (>70) to prevent emotional overtrading.
