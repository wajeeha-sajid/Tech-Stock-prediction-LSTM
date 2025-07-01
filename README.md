# 📈 Tech Stock Price Forecasting using LSTM

This project performs time-series analysis and forecasting on major tech company stocks — Apple, Google, Amazon, and Microsoft — using data from Yahoo Finance. It includes both detailed exploratory data analysis (EDA) and an LSTM-based deep learning model to forecast Apple stock prices.



## 📊 Overview

- Extract historical stock data using Yahoo Finance API  
- Visualize trends, trading volume, and daily returns  
- Analyze pairwise relationships and correlations  
- Build and train an LSTM model to predict closing prices  
- Evaluate model performance using RMSE



## 📁 Files Included

- `Stock_Market_Forecasting_using_LSTM.ipynb` — Full notebook including EDA, preprocessing, modeling, and forecasting  
- `requirements.txt` — All required libraries  




## 🔍 Key Features

- 📈 Multi-company stock price analysis  
- 🧠 LSTM deep learning model for prediction  
- 📊 Visualizations: Moving averages, correlations, returns  
- 🧪 Evaluation with RMSE metric  
- 🧰 Uses `yfinance`, `pandas_datareader`, and `TensorFlow/Keras`



## 🧠 Results

- Predicted Apple stock closing prices using last 60 days as input sequence  
- Achieved RMSE: ~`your_value_here`  
- Plotted actual vs. predicted prices



## 📦 Data Source

- **Yahoo Finance** via `yfinance` API  
- Live data pulled directly in the notebook using:  
  `yfinance.download(['AAPL', 'GOOG', 'MSFT', 'AMZN'], start, end)`



## 🧰 Installation

```bash
pip install -r requirements.txt


## 👩‍💻 Author

**Wajeeha Sajid**  
Electrical and Computer Engineering  
[GitHub Profile](https://github.com/wajeeha-sajid)
 

