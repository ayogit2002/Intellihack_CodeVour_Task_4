# Stock Price Prediction Challenge

## Overview
This project aims to predict stock closing prices 5 trading days into the future using historical stock price data. The solution follows a structured approach involving exploratory data analysis, feature engineering, model development, evaluation, and submission of results.

## Approach

### Exploratory Data Analysis (EDA)
- Identified trends, seasonality, and anomalies.
- Visualized stock price movement and key patterns.
- Engineered meaningful features (e.g., moving averages, volatility indicators).

### Model Development
Tested multiple models including:
- Linear Regression
- Random Forest
- LSTM (Long Short-Term Memory networks)

Evaluated models based on RMSE and directional accuracy.
Selected the best-performing model based on statistical metrics and trading performance.

## Evaluation Metrics
- **Root Mean Squared Error (RMSE)** for accuracy.
- **Directional accuracy** to assess predictive value for trading.

## Predictions
- Generated future stock price predictions.
- Output saved in `predictions.csv`.

## Reproducibility
To reproduce results:
1. Install dependencies using:
   ```bash
   pip install -r requirements.txt
   ```
2. Run the Jupyter Notebook:
   ```bash
   jupyter notebook stock_price_prediction.ipynb
   ```
3. Review outputs and visualizations.

## Limitations & Future Improvements
- **Data Limitations:** More historical data could improve model accuracy.
- **Feature Enhancements:** Additional financial indicators could refine predictions.
- **Advanced Models:** Incorporating ensemble learning or hybrid models may enhance performance.

## Files
- `stock_price_prediction.ipynb`: Jupyter notebook with complete workflow.
- `eda_report.pdf`: Detailed EDA report.
- `model_selection.pdf`: Documentation on model comparison and selection.
- `predictions.csv`: Final predicted stock prices.
- `README.md`: Summary and instructions.
