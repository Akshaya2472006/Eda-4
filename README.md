# 📈 Shopify Stock Market Analysis using Python

## 📌 Overview
This project performs Exploratory Data Analysis (EDA) on Shopify stock market data using Python. The analysis focuses on stock price trends, trading volume, daily returns, and rolling volatility to gain insights into historical stock performance.

## 🎯 Objectives
- Analyze Shopify stock price movements.
- Visualize Open, High, Low, and Close prices.
- Examine trading volume patterns.
- Calculate and analyze daily returns.
- Measure market volatility using rolling statistics.

## 🛠️ Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## 📂 Dataset Features
- Date
- Open
- High
- Low
- Close
- Adj Close
- Volume

## 📊 Analysis Performed

### 1. Data Exploration
- Dataset inspection using `head()`
- Data types and missing values check using `info()`
- Statistical summary using `describe()`

### 2. Stock Price Trend Analysis
Visualized historical Open, High, Low, and Close prices to identify growth patterns and market fluctuations.

### 3. Trading Volume Analysis
Analyzed stock trading activity through volume trends.

### 4. Daily Closing Price Analysis
Examined the movement of closing prices over time.

### 5. Daily Return Calculation
Calculated percentage daily returns using:

```python
df['daily_return'] = df['close'].pct_change()
```

### 6. Rolling Volatility Analysis
Computed 30-day rolling volatility to measure market risk.

```python
rolling_volatility = df['daily_return'].rolling(window=30).std()
```

## 📈 Key Insights
- Shopify stock shows significant long-term growth.
- Trading volume spikes often coincide with major price movements.
- Daily returns fluctuate around zero with periods of high volatility.
- Rolling volatility highlights changing market risk levels over time.

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/Akshaya2472006/Eda-4.git
```

2. Install required libraries

```bash
pip install pandas numpy matplotlib
```

3. Open Jupyter Notebook and run all cells.

## 📷 Visualizations Included
- Stock Price Trend
- Trading Volume Plot
- Daily Closing Price Plot
- Daily Return Plot
- Rolling Volatility Plot

## 🔮 Future Enhancements
- Moving Average Analysis
- RSI Indicator
- Bollinger Bands
- Time Series Forecasting
- Machine Learning-Based Stock Prediction

## 👨‍💻 Author
**Akshaya**

BCA Student | Aspiring Data Analyst | UI/UX Enthusiast

## ✅ Conclusion
This project demonstrates the use of Python for financial data analysis through visualization and statistical techniques. It provides valuable insights into stock performance, trading activity, daily returns, and market volatility.
