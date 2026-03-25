# Trader Sentiment Analysis

## Overview
This project analyzes trader behavior using market sentiment (Fear & Greed Index) and trading data.

## Objective
To understand how market sentiment affects:
- Profitability (PnL)
- Trading frequency
- Risk (trade size)

## Steps Performed
1. Data Cleaning
2. Date Conversion and Alignment
3. Merging datasets
4. PnL Analysis
5. Trade Frequency Analysis
6. Risk Analysis

## Key Insights
- Traders earn highest profits during Extreme Greed conditions.
- Trading activity increases significantly during Extreme Fear periods.
- Trade size (USD) is higher during Fear, indicating higher risk-taking behavior.
- There is a mismatch between trader behavior and profitability:
  Traders take higher risk during fear, but profits are higher during greed.

## Strategy Recommendations
- Avoid overtrading during fear conditions and stick to a disciplined approach.
- Use trend-following strategies in greedy markets where momentum is strong.
- Reduce position size during volatile or uncertain market conditions.
- Focus on risk management instead of reacting emotionally to market movements.

## Dataset
Dataset is included in compressed format due to GitHub file size limitations.

Steps to use:
1. Extract the zip file
2. Place the extracted files inside a `data/` folder
3. Ensure it contains:
   - fear_greed_index.csv
   - historical_data.csv

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook
```
## Tools Used
Python
Pandas
NumPy
Matplotlib
Seaborn
