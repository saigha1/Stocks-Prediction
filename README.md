# Stocks-Prediction

A Stocks Prediction Engine: Advises actions (Buy, Hold or Sell) on stocks (AAPL, AMZN, NVDA, MSFT, GOOGL) 5 days ahead of time.

## Overview
iOS app that displays ML-powered buy/sell/hold signals for major stocks
using a custom XGBoost model deployed on AWS.

## Architecture
- iOS frontend: SwiftUI, MVVM pattern
- Backend: AWS Lambda, API Gateway, DynamoDB, EventBridge
- ML Model: XGBoost (54% accuracy, 5-day price direction)
- Data: Alpha Vantage API

## Tech Stack
Swift, Python, AWS (Lambda, DynamoDB, S3, API Gateway, EventBridge),
XGBoost, pandas, scikit-learn

## Screenshots
