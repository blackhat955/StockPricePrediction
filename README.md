# Stock Price Prediction with Random Forest and Python

This repository is dedicated to predicting future stock prices using the `yfinance` library for data retrieval and the Random Forest algorithm for handling categorical data. The project aims to enhance accuracy through backtracking techniques and feature engineering, particularly for minute-by-minute price changes.

## Overview

- **Data Retrieval:** The [`yfinance`](https://pypi.org/project/yfinance/) library is employed to efficiently fetch historical stock data from Yahoo Finance.

- **Algorithm:** The [Random Forest](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html) algorithm, implemented in Python using the scikit-learn library, is chosen for its robustness in handling categorical data and making accurate predictions.

- **Enhancements:**
  - **Backtracking Techniques:** The model's accuracy is iteratively improved by fine-tuning parameters using backtracking strategies.
  - **Feature Engineering:** Additional features are engineered to capture minute-by-minute price changes, providing a more nuanced input for the model.

## Implementation

The predictive model is implemented in Python, leveraging the following technologies:

- **Programming Language:** Python
- **Libraries:**
  - [`yfinance`](https://pypi.org/project/yfinance/): For efficient retrieval of historical stock data.
  - [scikit-learn](https://scikit-learn.org/): Utilized for implementing the Random Forest algorithm.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/blackhat955/StockPricePrediction.git
