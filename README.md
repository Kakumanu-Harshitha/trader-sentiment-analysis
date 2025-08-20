# trader-sentiment-analysis
# Project Overview
This project analyzes the relationship between the Bitcoin Fear & Greed Index and the historical performance of traders on the Hyperliquid platform. The primary objective is to uncover hidden patterns in trader behavior and deliver data-driven insights that can be used to develop smarter, more effective trading strategies.

# Datasets
Bitcoin Market Sentiment: Daily data from the Fear & Greed Index, classifying market sentiment into categories like "Extreme Fear," "Fear," "Neutral," "Greed," and "Extreme Greed."

Historical Trader Data: Transaction-level data from Hyperliquid, including details on individual trades such as profit/loss (PnL), size, and direction (long/short).

# Key Insights & Visualizations
The analysis yielded five key insights into trader behavior and performance.

### 1. Finding: Profitability is Highest in Fearful Markets
The analysis shows a clear contrarian pattern: traders achieve their highest average profits during periods of "Extreme Fear." Conversely, they experience the largest average losses when the market is in "Extreme Greed." This suggests that buying into market panic is rewarded, while chasing euphoric rallies is punished.

### 2. Finding: Traders Risk More When They Should Be Cautious
The data reveals that traders increase their average position size as the market becomes greedier. This means they take their biggest financial risks at the exact moment their profitability is at its lowest, a classic behavioral trap driven by overconfidence at market tops.

### 3. Finding: Trade Direction Should Adapt to Sentiment
A trader's directional bias should adapt to the market's mood. Long (BUY) positions are most profitable during "Fear," while Short (SELL) positions only become profitable, on average, during periods of "Greed."

### 4. Finding: "Greed" Creates a High-Risk, Unpredictable Environment
The distribution of trade outcomes shows that trading during "Greed" is extremely volatile. The wide range of results and a median profit of $0.00 indicate a high-risk environment where a few massive wins skew the average, while the typical trade is not profitable.

### 5. Finding: The High Win Rate During "Greed" Is a Trap
Surprisingly, traders have the highest percentage of winning trades during "Extreme Greed." This is a deceptive trap, as it shows traders are securing many small wins while their few losses are so catastrophic they erase all the gains, leading to an overall negative performance.
# Requirements:
Pandas

Numpy

Matplotlib

seaborn

# programming languages:
Python

# owner:
[Kakumanu-Harshitha](https://github.com/Kakumanu-Harshitha)
