# 📈 Stock Price Prediction Using Linear Regression

This project is a machine learning pipeline to predict the **next-day closing price of Apple (AAPL)** stock using technical indicators and historical price data. The goal is to evaluate how well a linear regression model can forecast price movements, and to experiment with alternative models for better accuracy.

## 🧠 Features Used

- `Close`: Last traded price of the day
- `Volume`: Daily trading volume
- `MACD`: Moving Average Convergence Divergence
- `Signal`: MACD Signal Line
- `RSI`: Relative Strength Index
- `MA_10`: 10-day Moving Average

## 🛠️ Tech Stack

- Python
- [yfinance](https://pypi.org/project/yfinance/) for historical stock data
- scikit-learn for modeling and metrics
- pandas for data manipulation
- NumPy for numerical operations

## 🗂️ Project Structure

- ML_project_Stock_Pred.ipynb   # Main script with feature engineering and modeling
- requirements.txt   # Required Python packages
- README.md  # Project documentation
