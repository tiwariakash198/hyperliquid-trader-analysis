## ***Hyperliquid Trader Behavior & Sentiment Analysis***
This project provides a comprehensive behavioral analysis of crypto traders on the Hyperliquid exchange, correlating transactional data with market sentiment indices.

#### ***📌 Project Overview***
The objective is to analyze how market sentiment ("Fear" vs. "Greed") influences trader profitability, execution style, and risk-taking. The study processes 211,224 trades across 32 unique accounts to identify resilient trading archetypes.

⚙️ Setup & Installation
To run this project locally, ensure you have Python installed, then follow these steps:

#### ***Clone the Repository:***

git clone https://github.com/tiwariakash198/hyperliquid-trader-analysis.git
cd hyperliquid-trader-analysis
Create a Virtual Environment (Optional but Recommended):

python -m venv venv
#### ***Activate on Windows:***
venv\Scripts\activate
#### ***Activate on Mac/Linux:***
source venv/bin/activate

Install Dependencies:

pip install pandas matplotlib seaborn jupyter

***Data Placement:***

Ensure the data/ folder contains the following files:

historical_data.csv

fear_greed_index.csv

#### ***🚀 How to Run***
Launch Jupyter Notebook:

Open your terminal in the project folder and run:

jupyter notebook

***Execute the Analysis:***

Open data_analysis.ipynb.

Run the cells sequentially (Shift + Enter) to perform data cleaning, merging, and visualization.

#### ***Review Results:***
The notebook will generate three key visualizations (visual_1_pnl.png, visual_2_aggression.png, and visual_3_segments.png) in the project directory.

#### ***🛠️ Assignment Structure***
### ***Part A: Data Preparation & Metric Creation***
Data Merging: Synchronized trade data with the daily Crypto Fear & Greed Index.

Feature Engineering: Created daily metrics for PnL, Win Rate, Taker Ratio, and Long/Short bias.

### ***Part B: Behavioral & Segment Analysis***
The Sentiment Paradox: Analysis of profits vs. win rates across regimes.

Trader Segmentation: Categorized accounts into Whales, Alphas, and Chasers.

### ***Part C: Actionable Strategic Outputs***
The "Volatility Alpha" Rule: Frequency/sizing strategy for Fear regimes.

The "Greed De-Risking" Rule: Leverage reduction guidelines for Extreme Greed.

#### ***📂 Deliverables***
data_analysis.ipynb: Complete technical workflow.

executive_summary.pdf: One-page summary of insights and rules
