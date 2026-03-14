
## ***Hyperliquid Trader Behavior & Sentiment Analysis***
This repository contains a comprehensive behavioral analysis of crypto traders on the Hyperliquid exchange. The project correlates high-frequency transactional data with the Crypto Fear & Greed Index to identify how market sentiment drives profitability and risk-taking behavior.

### ***📌 Project Overview***
The objective was to move beyond aggregate performance metrics and understand the psychological archetypes that define the market. By analyzing 211,224 trades across 32 unique accounts, this study identifies the execution styles that thrive in "Fear" versus those that struggle in "Greed".

### ***🚀 Key Features***

Behavioral Segmentation: Traders are categorized into Whales vs. Minnows (Size), Scalpers vs. Position Traders (Frequency), and Alphas vs. Chasers (Execution Style).


Sentiment Correlation: Analysis of performance metrics (PnL, Win Rate, and Drawdown) across five distinct market regimes.


FOMO Detection: Quantifying the shift from patient "Maker" orders to impulsive "Taker" orders as market sentiment warms.

### ***📊 Core Insights ***


The Profitability Paradox: While "Extreme Greed" offers the highest win rates (38.6%), the largest average daily profits ($5,328) are realized during Fear regimes.


The FOMO Signal: Aggression (Taker Ratio) scales linearly with market optimism, rising from 62% to 69% as traders lose patience during bull trends.


Resilience of Alphas: "Alpha" traders maintain a sentiment-proof win rate (42%-56%) across all regimes, whereas "Chasers" lose money during Extreme Fear.

### ***🛠️ Tech Stack***
Language: Python 3.14.2

Libraries: Pandas (Data Alignment), Matplotlib & Seaborn (Visual Analysis)

Environment: VS Code / Jupyter Notebook

### ***📂 Repository Structure***
data_analysis.ipynb: The complete technical workflow, from data cleaning to final visualizations.


executive_summary.pdf: A one-page high-level brief designed for executive stakeholders.

### ***💡 Strategic Recommendations ***


Fear Strategy: Increase trade frequency by 20% for Alpha/Whale segments to capture mean-reversion alpha.


Greed Strategy: Reduce position sizes by 40% and strictly utilize Limit (Maker) orders to avoid the high costs of FOMO-driven entries.