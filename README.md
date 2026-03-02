# Predicting Future Stock Prices (Short-Term)

## Objective
The objective of this project is to predict the next day's closing stock price using historical stock market data. The project demonstrates data preprocessing, exploratory analysis, regression modeling, and prediction visualization using machine learning techniques.

## Dataset Used
Stock market data retrieved from Yahoo Finance using the yfinance API.

Stock Selected:
- Tesla (TSLA)

Features:
- Open
- High
- Low
- Volume

Target:
- Next Day Closing Price

## Tasks Performed
- Data loading using yfinance API
- Data inspection and preprocessing
- Feature engineering
- Data visualization
- Linear Regression model training
- Model evaluation
- Prediction visualization

## Model Applied
- Linear Regression

## Key Results
- Model successfully captured short-term price trends
- Predictions closely followed actual values during stable periods
- Demonstrated effectiveness of regression models for financial forecasting

## How to Run
1. Clone repository
2. Install dependencies:
   pip install -r requirements.txt
3. Open notebook:
   jupyter notebook Stock_Price_Prediction.ipynb
4. Run all cells

## Conclusion
This project shows how machine learning can be applied to time-series financial data for short-term prediction tasks.
