# bitcoin_-trade_-analysis# Bitcoin Market Sentiment vs Trader Performance Analysis

## Overview

This project analyzes the relationship between Bitcoin market sentiment and trader performance using historical trading data and the Fear & Greed Index.

## Objective

The objective is to understand how market sentiment influences:

* Trader profitability
* Trading volume
* Buy/Sell behavior
* Position sizing
* Overall trading performance

## Datasets Used

### 1. Bitcoin Fear & Greed Index Dataset

Columns:

* Date
* Value
* Classification (Extreme Fear, Fear, Neutral, Greed, Extreme Greed)

### 2. Historical Trader Dataset

Columns:

* Account
* Coin
* Execution Price
* Size USD
* Side
* Closed PnL
* Timestamp
* Fee
* Trade ID

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

## Key Findings

### Profitability Analysis

* Highest Average PnL: Extreme Greed (67.89 USD)
* Highest Total Profit: Fear (3.36 Million USD)

### Trading Volume Analysis

* Largest average trade size observed during Fear periods.

### Trader Behavior Analysis

* More buying activity during Extreme Fear.
* More selling activity during Extreme Greed.

### Trader Performance

* 211,224 trades analyzed.
* 32 unique traders analyzed.
* Most traders remained profitable overall.

## Visualizations

* Average PnL by Sentiment
* Total PnL by Sentiment
* Trade Size by Sentiment
* Buy vs Sell Analysis
* Top Traders Analysis

## Conclusion

The analysis demonstrates a clear relationship between market sentiment and trading behavior. Traders tend to accumulate positions during fear and take profits during greed, indicating sentiment-driven decision making.

## Author

Sagar Kethwas
B.Tech (Data Science)
