# 📈 Stock Price Forecasting using LSTM

This project implements a deep learning approach to predict Microsoft stock closing prices using historical time-series data and Long Short-Term Memory (LSTM) networks. It simulates a realistic financial forecasting workflow used in quantitative trading and investment analysis.

---

## 🔍 Project Overview

- 🧠 **Model Type:** Long Short-Term Memory (LSTM) Neural Network
- 💼 **Data Source:** Microsoft stock data from Yahoo Finance
- 📊 **Problem:** Time-series regression for next-day stock price prediction
- ⚙️ **Frameworks:** Keras, TensorFlow, Pandas, Matplotlib

---

## 🧪 Features

- Download real stock price data with `yfinance`
- Visualize historical price trends
- Normalize & prepare sequences using a sliding window method
- Train an LSTM model to predict future prices
- Plot predicted vs actual prices for visual performance comparison

---

## 📦 Technologies Used

| Tool/Library | Purpose |
|--------------|---------|
| `yfinance`   | Download stock market data |
| `pandas`     | Data preprocessing |
| `matplotlib` | Data visualization |
| `sklearn`    | Normalization |
| `keras`      | LSTM model building |
| `numpy`      | Numerical operations |

---

## 🚀 How to Run

1. Install dependencies:
```bash
pip install yfinance pandas matplotlib scikit-learn keras tensorflow
```

2. Run the script:
```bash
python stock_forecasting_lstm_commented.py
```

3. Check the output graph to see predicted vs actual prices!

---

## 📌 Use Case

This project mimics entry-level signal extraction techniques used in quant finance, using neural networks to model and forecast price movement patterns.

---

## 🙌 Author

Maitrri Jayant Chandra  
MS in Applied Data Science, University of Southern California  
[LinkedIn](https://linkedin.com/in/maitrrichandra) | [GitHub](https://github.com/Maitrri)