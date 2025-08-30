# Stock Price Prediction using Machine Learning

## Description
Stock Price Prediction using Machine Learning. A simple project applying Linear Regression with feature scaling and hyperparameter tuning to predict next day stock prices. Includes data preprocessing, model training, evaluation, and visualization of results.

## Features
- Fetch historical stock data using Yahoo Finance API (`yfinance`).
- Preprocess data with feature scaling and handle missing values.
- Train a Linear Regression model using a Pipeline.
- Hyperparameter tuning with GridSearchCV.
- Visualize actual vs predicted stock prices.
- Predict next-day stock closing prices.

## Installation
1. Clone this repository:
```bash
git clone https://github.com/your-username/stock-price-prediction.git
```
2. Install required libraries:

```bash
pip install yfinance pandas numpy matplotlib seaborn scikit-learn
```
## Usage

1. Open the notebook `Stock_Price_Prediction.ipynb` in Google Colab or Jupyter.

2. Run each cell sequentially.

3. Modify the stock symbol in the code to predict for a different company.

4. Observe plots, metrics, and the predicted next-day price.

## Learnings

 - Fetching and cleaning financial data

 - Feature engineering for stock price prediction

 - Using `Pipeline` and `GridSearchCV` for ML workflows

 - Evaluating models with MAE and R²

 - Visualizing predictions and residuals

## Future Improvements

 - Add more features like RSI, MACD, Bollinger Bands

 - Experiment with advanced models (Random Forest, XGBoost, LSTM)

 - Build a simple web app to interact with predictions

## Author

Syed Asad Abbas Rizvi
