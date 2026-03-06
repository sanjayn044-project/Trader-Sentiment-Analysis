# Trader Performance vs Market Sentiment Analysis

## Overview

This project analyzes the relationship between **Bitcoin market
sentiment (Fear/Greed Index)** and **trader behavior and performance**
on the Hyperliquid trading platform.

The goal is to identify patterns between **market sentiment and trading
outcomes**, which can help design **smarter trading strategies and risk
management rules**.

------------------------------------------------------------------------

# Dataset

Two datasets were used in this analysis.

### 1. Bitcoin Market Sentiment Dataset

Contains the daily **Fear and Greed index**.

Columns include: - Date - Sentiment Classification (Fear / Greed) -
Sentiment Value

### 2. Historical Trader Data (Hyperliquid)

Contains detailed trade-level data including: - Account (wallet
address) - Symbol - Execution Price - Trade Size (USD) - Side (Buy /
Sell) - Timestamp - Closed PnL - Fees - Position information

------------------------------------------------------------------------

# Objective

The objective of this analysis is to understand:

-   How trader performance changes during **Fear vs Greed market
    conditions**
-   Whether traders change behavior based on market sentiment
-   Which types of traders perform better in different sentiment
    environments
-   How insights from sentiment data can be used to design **better
    trading strategies**

------------------------------------------------------------------------

# Tools & Technologies

The analysis was performed using:

-   Python
-   Pandas
-   NumPy
-   Matplotlib
-   Seaborn
-   Jupyter Notebook

------------------------------------------------------------------------

# Project Structure

trader-sentiment-analysis/

data/ - fear_greed_index.csv - historical_data.csv

notebook/ - trader_sentiment_analysis.ipynb

charts/ - output_visualizations.png

README.md

------------------------------------------------------------------------

# Setup Instructions

## 1. Clone the repository

git clone https://github.com/yourusername/trader-sentiment-analysis.git
cd trader-sentiment-analysis

------------------------------------------------------------------------

## 2. Install required packages

pip install pandas numpy matplotlib seaborn jupyter

------------------------------------------------------------------------

## 3. Place the datasets

Put the following files inside the **data folder**:

-   fear_greed_index.csv
-   historical_data.csv

------------------------------------------------------------------------

# How to Run the Project

Open the Jupyter Notebook and run the analysis:

jupyter notebook

Then open:

notebook/trader_sentiment_analysis.ipynb

Run all cells sequentially to: 1. Load datasets 2. Clean the data 3.
Merge sentiment with trading data 4. Generate trader performance metrics
5. Produce charts and insights

------------------------------------------------------------------------

# Key Metrics Analyzed

-   Daily PnL per trader
-   Trade frequency per day
-   Average trade size
-   Long vs Short ratio
-   Win rate
-   Trader segmentation

------------------------------------------------------------------------

# Trader Segmentation

Traders were grouped into:

-   Frequent vs Infrequent traders
-   High-volume vs Low-volume traders
-   Profitable vs Losing traders

------------------------------------------------------------------------

# Key Insights

1.  **Higher Trading Activity During Greed** Trade frequency increased
    during Greed sentiment periods.

2.  **Larger Position Sizes During Greed** Traders tend to take larger
    positions when market sentiment is Greed.

3.  **Higher Volatility During Fear** Fear periods show larger swings in
    trader profits and losses.

------------------------------------------------------------------------

# Strategy Recommendations

### Strategy 1 --- Risk Reduction During Fear

During Fear sentiment, traders should reduce leverage and position
sizes.

### Strategy 2 --- Controlled Aggression During Greed

During Greed periods, traders may increase trading frequency but should
limit leverage.

------------------------------------------------------------------------
##**Drive link**- https://drive.google.com/drive/folders/1fBdxWRttspeX6gX58jFcw-IL_Ovmctx1?usp=sharing
# Author

Sanjay N\
Data Analyst \| Python \| SQL \| Power BI
