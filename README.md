# Financial-Market-Analytics-Dashboard
Financial market analytics project leveraging yfinance, Pandas, and Matplotlib to compute technical indicators (RSI, MACD, SMA/EMA), volatility models, sector heatmaps, and cross-asset trend analysis in a Jupyter environment.

##  1. Project Overview & Purpose
This project provides a Financial Market Analytics Dashboard designed to help non-technical audiences understand how the stock market works, how to interpret key technical indicators, and how analysts use data to evaluate price movement and market behavior.

The goal of this project is to make financial analytics simple, intuitive, and educational, even for people with little or no background in finance. Using clean market data from the Yahoo Finance API (yfinance), the dashboard walks users through the fundamentals of:

- How stock prices move over time
- What causes momentum, reversals, or volatility
- How different sectors behave relatively to each other
- Which indicators traders and analysts rely on  
- How to identify strong vs. weak stocks  
- How data can support forecasting and investment decisions  

---
## 2. Data Used
This dashboard uses the **Yahoo Finance API (`yfinance`)** to download historical OHLCV data:

- **Open, High, Low, Close, Adjusted Close, Volume**
- Major indices: **S&P 500 (SPY), NASDAQ 100 (QQQ), Russell 2000 (IWM)**
- Sector ETFs: **Tech (XLK), Financials (XLF), Energy (XLE)**
- Large-cap stocks: **AAPL, MSFT, NVDA, AMZN**

This data supports:

- Price trend analysis  
- Momentum detection  
- Sector rotation insights  
- Volatility measurement  
- Correlation and diversification analysis
  
---
## 3. Technical Indicators Created
To help non-technical users understand how financial analysts interpret market conditions, this proejct computes several widely used technical indicators:
### **Trend Indicators**
- Simple Moving Average (**SMA**)  
- Exponential Moving Average (**EMA**)  

### **Momentum Indicators**
- **RSI (Relative Strength Index)**  
- **MACD (Moving Average Convergence Divergence)**  

### **Volatility Indicators**
- Rolling Standard Deviation  
- **ATR (Average True Range)**  

### **Price Pattern Indicators**
- **Bollinger Bands**  

### **Volume Analysis**
- Volume trend detection  

These indicators are commonly used by traders, analysts, and portfolio managers.

---
## 4. How This Helps Explain & Forecast Market Movement
The dashboard helps answer important financial questions in a beginner-friendly way:

- **Is the stock trending upward or downward?**  
- **Is the asset overbought or oversold?**  
- **Is volatility increasing or decreasing?**  
- **Which sectors are currently outperforming?**  
- **How correlated are major indices and large-cap stocks?**  
- **Which assets show strong momentum signals?**  
- **Is the current trend likely to continue?**  

By combining indicators with cross-asset and sector comparison, the dashboard provides a simplified but powerful explanation of market behavior—similar to how Bloomberg Terminal users interpret market signals.

---


