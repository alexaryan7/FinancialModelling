# FinancialModelling
A Very small scale Financial Model based on RandomForestRegressor for FinClub

# 📈 Financial Modelling for Investment Decision Making

This project is a comprehensive financial modelling pipeline built using Python and Jupyter Notebook. It guides users through the core steps involved in investment analysis — from data acquisition and cleaning to portfolio optimization, risk management, and machine learning-based forecasting.

---

## Modules Overview

## **Module 1: Data Cleaning**
- Loads historical stock data from the S&P 500.
- Standardizes column names.
- Converts timestamps and ensures consistent formatting.
- Outputs cleaned CSV and Excel files for further processing.

## **Module 2: Return Analysis**
- Calculates **daily and monthly returns**.
- Computes **volatility**, **Compound Annual Growth Rate (CAGR)**, and **Sharpe Ratio**.
- Evaluates **Maximum Drawdown** to measure downside risk.
- Helps in understanding each stock's risk-return characteristics.

## **Module 3: Portfolio Construction & Optimization**
- Constructs an **equally weighted** and **optimized portfolio** using mean-variance theory (Modern Portfolio Theory).
- Uses `scipy.optimize` to compute the best weights that maximize Sharpe ratio.
- Saves final portfolio weights as a CSV file.
- Visualizes performance with cumulative returns.

## **Module 4: Risk Management**
- Computes and visualizes:
  - **Value at Risk (VaR)** at a 95% confidence level.
  - **Conditional VaR (Expected Shortfall)**.
  - Drawdown charts to analyze worst-case scenarios.
- Introduces practical risk measures to balance return expectations.

## **Module 5: Machine Learning Forecasting**
- Uses `RandomForestRegressor` to forecast stock prices.
- Generates lag-based features (`t-1`, `t-2`, `t-3` days).
- Splits the dataset into train/test sets.
- Measures performance using:
  - **R² Score**
  - **Mean Squared Error**
- Provides predicted vs. actual plots for evaluation.

---

## Tech Stack

- **Language**: Python 3.10
- **IDE**: Jupyter Notebook
- **Libraries**:
  - `pandas`, `numpy`, `matplotlib`, `seaborn`
  - `scikit-learn`
  - `scipy.optimize`
  - `openpyxl`
- **Data Source**: Cleaned historical S&P 500 stock data (CSV)



