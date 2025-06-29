# TradingAnalysis
The trading analysis project aims to explore the relationship between trading performance and market sentiment and it unpacks the hidden insights to provide smarter trading strategiesand 
### **Objective**

To explore the relationship between trader performance and market sentiment using real-world trading data from PrimeTrade.ai. The project aimed to extract actionable insights and uncover hidden behavioral patterns to inform smarter trading strategies.

### **Dataset Overview**

- **Historical Trading Data** (May & Dec 2023, full 2024, partial 2025)
- **Fear & Greed Index** (Sentiment data)
- **Over 210,000 trades across ~247 unique coins**
To uncover actionable insights, I adopted a structured analytical workflow. The initial phase involved a temporal decomposition of the data, analyzing each year (2023-2025) independently to identify year-specific market dynamics. Subsequently, I performed a feature enrichment by integrating the Fear and Greed Index to quantify the interplay between market sentiment and trading success. For behavioral segmentation, I applied Mini-Batch KMeans, a scalable clustering technique designed for efficiency with large datasets. The final step involved using Principal Component Analysis (PCA) to reduce dimensionality and visualize the resulting clusters, providing a clear map of distinct trader cohorts and their performance characteristics.
To get some key insights from my analysis refer to the analysis summary PDF .
