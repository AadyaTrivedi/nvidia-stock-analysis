# 📊 NVIDIA Stock Data Analysis (Pandas & NumPy Project)

## 🚀 Overview

This project analyzes NVIDIA stock data using Python, Pandas, and NumPy to understand price trends, market behaviour, and technical indicators.
It focuses on feature engineering, trend-based signal analysis, and statistical insights derived from historical stock data.

---

## 📁 Dataset

* Historical NVIDIA stock dataset (1999–present)
* Features include OHLC prices, volume, moving averages (SMA), RSI, and key events

---

## 🛠️ What I Did

* Cleaned and preprocessed the dataset
* Converted date column to datetime format
* Handled missing values (stock splits, key events)
* Created new features:

  * Daily price change
  * Daily return (%)

---

## 📈 Analysis Performed

* Percentage of bullish vs bearish days
* Average daily return, maximum gain, and maximum loss
* Trend analysis using:

  * SMA 20 (short-term)
  * SMA 50 (mid-term)
  * SMA 200 (long-term)
* Generated trading signals:

  * Trend Signal (Above/Below SMA 20)
  * Trend Strength (Uptrend/Downtrend)
  * Golden Cross (Long-term bullish signal)

---

## ⚡ NumPy Integration

* Used `np.where()` for efficient vectorized signal generation
* Computed stock volatility using the standard deviation of returns
* Applied NumPy-based filtering and statistical analysis for performance comparison

---

## 🔥 Key Insights

* Stock shows nearly balanced bullish and bearish days (~50/50 split)
* Slight tendency toward downtrend phases, but not significantly dominant
* Golden cross signals occur frequently, indicating cyclical bullish periods rather than sustained trends
* Strong bullish conditions (alignment across all indicators) are relatively rare but signal high momentum phases
* The stock exhibits **consistent volatility (~0.44%)** across both uptrend and downtrend phases
* Price fluctuations remain stable regardless of market direction

---

## 🧠 Learning Outcomes

* Hands-on experience with Pandas and NumPy for data analysis
* Understanding of financial indicators (SMA, RSI, trends)
* Feature engineering and signal-based analysis
* Applying statistical methods (volatility, conditional analysis) to real-world data

---

## ⚙️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Streamlit

---

