***Trader Behavior Insights: PnL and Market Sentiment Analysis***

**Overview**
This project investigates how market sentiment (Fear vs. Greed) influences trader behavior and performance (PnL). By analyzing real trading data across accounts and symbols, the study uncovers meaningful patterns that can guide better trading strategies and risk management.

**Objectives**
Understand how sentiment influences PnL across different coins and accounts.

Identify trading symbols with strong sentiment–performance relationships.

Uncover behavior patterns linked to consistent gains or losses.

Apply simple ML (KMeans) to group accounts by trade performance and activity.

**Context**
This assignment was done as part of an application for the Junior Data Scientist – Trader Behavior Insights role at BajARangs/PrimeTrade. The focus was not just on analysis, but on uncovering real, actionable insights — going beyond basic charts into behavioral patterns, lag effects, and market dynamics.

**Tools & Libraries Used**
Python 3.9+

pandas, numpy – for data wrangling

matplotlib, seaborn, plotly – for static and interactive visualizations

scikit-learn – for clustering (KMeans)

datetime, warnings, collections – for preprocessing and analysis

**Key Insights**
Sentiment-PnL Gaps: Some symbols perform better in “Fear” mode, while others thrive during “Greed.”

Fee Sensitivity: Traders with higher net PnL tend to incur lower relative fees.

Buy vs. Sell Asymmetry: Sell trades under Fear often generate sharper losses.

Sentiment Lag: Sentiment often impacts PnL with a lag of 1 day, especially for volatile coins.

Trader Archetypes: Using KMeans, accounts were grouped based on volume and profitability — revealing clear patterns of aggressive vs. cautious traders.

**How to Use**
Clone this repo or download the folder.

Open the notebook: notebooks/eda_trader_sentiment_analysis.ipynb

Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the notebook to explore the analysis and insights.

**Deliverables**
EDA Notebook – all analysis and visualization
Executive Summary – top-level insights for decision-makers
Summary Tables – coins, sentiment patterns, PnL clusters
Cleaned Dataset – for reuse or model building
Optional ML Model – KMeans clustering of accounts

**Author**
Aditi Sahu
M.Tech in GeoInformatics, IIT Kanpur
[aditisahu24@iitk.ac.in]
[[LinkedIn or GitHub profile link](https://github.com/aditisahu911)]

