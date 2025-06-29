📊 Trading Analysis & Behavioral Insights
This project explores how trader performance correlates with market sentiment using real-world data from PrimeTrade.ai. By analyzing over 210,000 trades across 247 unique coins, the study reveals behavioral patterns, asset-level performance, and sentiment-driven strategies to support data-informed trading decisions.

🚀 Objective
To extract actionable insights and uncover hidden behavioral patterns by:

Analyzing year-wise trading dynamics (2023–2025)

Integrating Fear & Greed Index to map sentiment with profitability

Clustering trader behaviors using Mini-Batch KMeans

Visualizing dimensionality-reduced trader segments using PCA

📂 Dataset Overview
Historical Trade Data: May & Dec 2023, Full 2024, Partial 2025

Sentiment Data: Fear & Greed Index

Volume: Over 210,000 transactions across 247 unique cryptocurrencies

📈 Key Analyses Performed
🔹 Temporal Insights
📉 Volatility in BUY/SELL trends peaked in Aug-Sep 2024

⏳ Execution Price trends analyzed for 2023 using Plotly interactive charts

🔹 Coin-Wise Performance (2023)
High-Risk: SOL, MATIC

Low-Risk: ILV, TIA

Popular but Unprofitable: JTO

High ROI: AAVE, BTC

🔹 Top Profitable Coins (2023)
Ranked by average closed PnL.

🔹 Entry Timing Recommendations (2024)
Based on recurring execution price patterns:

107: Ideal buy in week 1

ZRO, HYPE, FTT: Days 19–25

🔹 Profitability by Starting Position
Traders with negative starting positions profited most with WLD, HYPE

BTC had universal appeal regardless of capital

PURR/USDC performed well for positive start positions

🧠 Market Sentiment Analysis
🔸 Does sentiment affect profit?
✅ Highest profitability during Fear

❌ Most losses during Greed

🔸 Trader behavior under sentiment
Higher fees paid during Fear

Frequent direction changes during Fear, Extreme Fear, and Greed

Larger trade sizes taken during Greed

🔸 Coin performance under sentiment
Volatility and profitability vary drastically

Created a Trader Performance Score: Closed PnL / Fee

🛠 Tools & Technologies Used
Python, Pandas, NumPy

Plotly, Seaborn, Matplotlib

Scikit-learn for clustering and PCA

Jupyter Notebook for analysis

PDF Reports & Interactive Dashboards

📌 Key Takeaway
Fear outperforms Greed in trading strategy. Profitability is often counterintuitive, and data-driven timing + coin selection is crucial for optimal returns.
