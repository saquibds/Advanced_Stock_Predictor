# 🚀 Advanced Stock Price Predictor (Streamlit + LSTM)

This project is a real-time, interactive stock price prediction app built with Streamlit and LSTM. It uses multiple stock features (Open, High, Low, Close, Volume) to train a neural network and make predictions based on user input.

## 🌐 Live Demo (optional)
[Add Streamlit Cloud URL if deployed]

## 🛠 Tech Stack
- Python
- Streamlit
- yfinance
- LSTM (Keras, TensorFlow)
- Pandas, NumPy, Scikit-learn
- Matplotlib

## 🔥 Features
- Choose any stock ticker (e.g., AAPL, TSLA, RELIANCE.NS)
- Pulls 5+ years of historical stock data
- Uses Open, High, Low, Close, Volume (OHLCV)
- LSTM model with 2 layers and 20+ epochs
- Interactive visualization of actual vs. predicted prices

## 📦 How to Run Locally

1. Clone the repo or download files  
2. Create virtual env (optional)  
3. Install dependencies:

```bash
pip install -r requirements.txt

Run the app:
streamlit run advance_prediction.py
