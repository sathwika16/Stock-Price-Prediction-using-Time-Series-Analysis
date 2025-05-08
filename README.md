# 📈 ME228 Final Project: Stock Price Prediction Using LSTM
## 📝 Project Description

This project implements a deep learning approach to predict stock prices using historical financial data obtained from Yahoo Finance. The focus is on **Apple Inc. (AAPL)** stock, and the model is built using a Long Short-Term Memory (LSTM) neural network, a type of recurrent neural network (RNN) particularly suited for time series forecasting.

---

## Data Source

- **Provider**: Yahoo Finance
- **Access Method**: [`yfinance`](https://pypi.org/project/yfinance/) Python library
- **Ticker Used**: `AAPL` (Apple Inc.)
- **Date Range**: 2015-01-01 to 2024-12-31

---

## Technologies & Libraries

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- yfinance
- scikit-learn
- TensorFlow / Keras

---

##  Model Overview

- **Preprocessing**: Normalization using `MinMaxScaler`
- **Model Type**: Sequential LSTM
- **Target Variable**: Closing stock price
- **Evaluation Metrics**:
  - Mean Squared Error (MSE)
  - Mean Absolute Error (MAE)
  - R-squared Score (R²)

---

## How to Run

1. **Install dependencies** (if not already installed):

   ```bash
   pip install yfinance pandas numpy matplotlib scikit-learn tensorflow
   ```

2. **Open the notebook**:

   ```
   projectma228.ipynb
   ```

3. **Run all cells** to fetch data, preprocess it, train the model, and evaluate results.

---

##  Notes

- The code and model were developed independently without any external templates.
- Make sure you are connected to the internet to fetch data using `yfinance`.
