# Visualizing Market Signals: A Technical Analysis of S&P 500 Price Trends

##  Project Overview

This project analyzes historical stock price data from the S&P 500 using widely recognized technical indicators—**Simple Moving Averages (SMA)**, **Bollinger Bands**, and the **Relative Strength Index (RSI)**—to extract actionable insights into market trends, volatility, and momentum. The analysis is visualized using Python in Google Colab to enable clarity and real-time interactivity.

Developed with a business-first lens, the goal is not algorithmic trading or model optimization but **executive-level insight generation** that supports portfolio decision-making, risk management, and strategic forecasting.

---

##  Key Insights

### 🔹 Trend Confirmation
- **SMA 20 and SMA 50 crossovers** are used to identify medium-term momentum shifts.
- These signals support strategic timing for equity entry and exit points, especially for multi-asset or actively managed portfolios.

### 🔹 Volatility Monitoring
- **Bollinger Bands** capture dynamic price volatility.
- Bands widen during turbulent periods and contract during stable conditions, providing useful inputs for volatility-aware asset allocation.

### 🔹 Momentum & Market Sentiment
- **RSI** highlights overbought (>70) or oversold (<30) conditions.
- Useful for detecting potential mean-reversion opportunities or price exhaustion in specific equities.

---

##  Strategic Relevance

| Use Case                     | Application Area                          |
|-----------------------------|-------------------------------------------|
| Tactical Portfolio Rebalancing | Enhances timing by signaling trend strength and reversals |
| Risk Flagging                | Identifies volatility clusters and overheated markets      |
| Quant Research Foundation    | Serves as a prototype for alpha signal engineering         |
| Executive Decision Support   | Visual insights can be shared in investment committee reviews |

---

##  Technical Stack

- **Python** (Pandas, Plotly, Pandas-TA)
- **Google Colab** for hosted execution and visualization
- **CSV Dataset** containing historical OHLC and volume data for a publicly traded S&P 500 company

---

##  Dataset Description

- Source: Kaggle / Yahoo Finance
- Columns: Date, Open, High, Low, Close, Volume
- Data was cleaned, sorted chronologically, and indexed by trading date

---

##  Visual Output

1. **SMA 20 & 50 Overlay**: Highlights bullish and bearish crossovers
2. **Bollinger Bands**: Captures price volatility trends and extremes
3. **RSI Plot**: Detects market overreactions and potential reversals

---

##  Project Goal

This project demonstrates how core technical indicators can be used to support business decisions in:
- Tactical asset allocation
- Trading strategy validation
- Market risk management
- Investor communication via clear data storytelling

