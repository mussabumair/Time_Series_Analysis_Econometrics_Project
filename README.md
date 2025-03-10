# Cryptocurrency Effect on Stock Market - Econometrics Project

## 📌 Project Overview

This research project explores the relationship between cryptocurrencies and traditional stock market indices, focusing on the impact of Bitcoin (BTC), Ethereum (ETH), Litecoin (LTC), and the Grayscale Bitcoin ETF (GBTC) on the NASDAQ 100 index. The study employs econometric techniques such as multiple regression analysis, correlation analysis, and time-series modeling to determine how fluctuations in crypto markets influence stock market movements.

## 🏆 Key Features

- **Data Collection:** Historical price data from Investing.com covering May 2017 to October 2024.
- **Econometric Modeling:** Uses multiple regression, correlation matrices, co-integration tests, and forecasting models.
- **Stationarity & Time-Series Analysis:** Includes ADF tests, ARIMA/ARMA models, and Johansen Co-Integration testing.
- **Statistical Diagnostics:** Checks for heteroskedasticity, multicollinearity, and autocorrelation to ensure model reliability.

## 📊 Data & Variables

- **Dependent Variable:** NASDAQ 100 Index
- **Independent Variables:**
  - BTC (Bitcoin)
  - ETH (Ethereum)
  - LTC (Litecoin)
  - GBTC (Grayscale Bitcoin ETF)
  - EUR/USD (Exchange Rate)

## 📈 Methodology

### 1️⃣ **Descriptive Statistics & Correlation Analysis**

- Normality checks using histograms, skewness, and kurtosis.
- Correlation analysis between crypto assets and NASDAQ 100.

### 2️⃣ **Regression Analysis**

- Multiple Linear Regression Model:
  ```math
  NASDAQ = β0 + β1(BTC) + β2(ETH) + β3(LTC) + β4(GBTC) + U
  ```
- Significance testing using t-values and p-values.

### 3️⃣ **Time-Series Analysis**

- **ADF Test:** Confirms stationarity at first difference I(1).
- **Johansen Co-Integration Test:** Identifies long-term relationships between cryptocurrencies and stock indices.
- **Granger Causality Test:** Determines predictive relationships between variables.

### 4️⃣ **Forecasting Using ARIMA Models**

- Selected **ARIMA(5,1,35)** based on model significance.
- Forecasts NASDAQ 100 movements based on cryptocurrency trends.

## 🛠 Key Findings

- **Strong Positive Correlation:** BTC and ETH show a strong correlation (0.92 and 0.86) with NASDAQ.
- **Volatility Spillover:** Crypto market fluctuations significantly impact stock market movements.
- **Predictive Relationship:** Bitcoin and Ethereum show a leading relationship with NASDAQ 100.
- **Model Accuracy:** ARIMA(5,1,35) effectively forecasts stock market movements with minimal error.

## 🔮 Future Enhancements

- Expand dataset to include more global stock indices.
- Incorporate macroeconomic factors (interest rates, inflation, monetary policy).
- Develop machine learning-based predictive models.

## 📜 References

- Data sourced from [Investing.com](https://www.investing.com/)
- Financial reports & academic papers on crypto-stock market correlation

## 🤝 Contributors

- **Mussab Bin Umair** & Raed Alvi

📌 **Note:** If using this work, please cite appropriately. 🚀

