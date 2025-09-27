This stock market analysis project is a notebook that explores and analyzes time-series data from several major technology stocks: **Apple (AAPL), Amazon (AMZN), Google (GOOG), and Microsoft (MSFT)**.

The project demonstrates how to retrieve and manipulate financial data, perform risk analysis, and even attempt to predict future stock prices using a deep learning method.

---

## Key Features and Topics

The analysis is structured around a series of key questions and technical methods:

### 1. Data Acquisition and Exploration
* **Source:** Stock data is reliably downloaded from the **Yahoo Finance website** using the **`yfinance` Python library**.
* **Time-Series Basics:** Handling time-series data, including recognizing that weekends are missing from the records.
* **Basic Analysis:** Reviewing **closing price** (the standard benchmark for tracking performance) [cite: 28] and **volume of sales** (an important input for technical traders).

### 2. Technical Analysis
* **Moving Average (MA):** Calculating the moving average for the stocks, which is a tool to smooth out price data by creating a constantly updated average price over a chosen period (e.g., 10, 20, or 50 days).
* **Daily Return:** Calculating the daily percentage change of the stock, which is necessary for deeper risk analysis.

### 3. Risk and Correlation Analysis
* **Stock Correlation:** Measuring the degree to which the daily returns of two stocks move in relation to each other, with a value between $-1.0$ and $+1.0$[cite: 46]. The notebook compares the correlation between all the selected stocks.
* **Risk Quantification:** Quantifying the **risk** of investing in a stock by comparing its **expected return** (mean of daily returns) with the **standard deviation** of its daily returns.

### 4. Stock Price Prediction
* **Forecasting Method:** Demonstrating an attempt to predict the future closing stock price of Apple Inc. using a **Long Short-Term Memory (LSTM)** method, a type of recurrent neural network.

---

## Technical Stack

* **Core Libraries:** `pandas`, `numpy`
* **Data Retrieval:** `yfinance`, `pandas_datareader`
* **Visualization:** `Matplotlib`, `Seaborn`
* **Modeling:** `keras` (for the LSTM model), `sklearn` (for data scaling)

---

## Goals Achieved

we have learned:

1.) What was the change in price of the stock over time?
2.) What was the daily return of the stock on average?
3.) What was the moving average of the various stocks?
4.) What was the correlation between different stocks'?
5.) How much value do we put at risk by investing in a particular stock?
6.) How can we attempt to predict future stock behavior? (Predicting the closing price stock price of APPLE inc using LSTM)
