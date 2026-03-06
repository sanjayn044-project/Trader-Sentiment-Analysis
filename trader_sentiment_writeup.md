## Trader Behavior vs Market Sentiment --- Summary

### Methodology

This analysis examines the relationship between **Bitcoin market
sentiment (Fear/Greed Index)** and **trader behavior on the Hyperliquid
platform**.

Two datasets were used: 1. Bitcoin Fear & Greed Index containing daily
sentiment classification. 2. Historical Hyperliquid trader data
containing trade execution details such as account, trade size, side,
timestamp, and closed PnL.

The analysis was performed using Python with Pandas, Matplotlib, and
Seaborn.

Workflow steps:

1.  Data Cleaning

-   Removed duplicate records
-   Checked for missing values
-   Converted timestamps into daily date format

2.  Dataset Alignment

-   Both datasets were aligned at the daily level
-   Trader data was merged with sentiment data using the date field

3.  Metric Creation The following metrics were calculated:

-   Daily PnL per trader
-   Trade frequency
-   Average trade size
-   Long vs Short ratio
-   Win rate by sentiment

4.  Trader Segmentation Traders were grouped into:

-   Frequent vs Infrequent traders
-   High-volume vs Low-volume traders
-   Profitable vs Losing traders

5.  Exploratory Analysis Visualizations were generated to compare trader
    behavior during Fear vs Greed market conditions.

------------------------------------------------------------------------

### Key Insights

Insight 1 --- Higher Trading Activity During Greed Trading activity
increases during Greed sentiment periods. This suggests traders are more
confident and participate more actively in bullish markets.

Insight 2 --- Larger Position Sizes During Greed Traders tend to open
larger positions when market sentiment is Greed, indicating higher risk
appetite.

Insight 3 --- Higher Profit Volatility During Fear Fear periods show
larger swings in profit and loss, suggesting markets are more unstable
and unpredictable.

Insight 4 --- Frequent Traders Adapt Better Frequent traders tend to
perform relatively better during Greed periods due to faster reactions
to market momentum.

------------------------------------------------------------------------

### Strategy Recommendations

Strategy 1 --- Risk Reduction During Fear During Fear market
sentiment: - Reduce position sizes - Lower leverage - Focus on risk
management

Strategy 2 --- Momentum Trading During Greed During Greed periods: -
Increase trade frequency carefully - Use momentum strategies - Limit
leverage to control drawdowns

Strategy 3 --- Segment-Based Strategy Frequent traders may benefit from
Greed markets, while less active traders should reduce exposure during
Fear periods.

------------------------------------------------------------------------

Overall, the analysis suggests that market sentiment influences trader
behavior and performance. Incorporating sentiment signals into trading
strategies can help improve decision-making and risk management.
