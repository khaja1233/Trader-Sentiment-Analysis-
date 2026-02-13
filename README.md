# Trader Sentiment Analysis

## Overview
This project analyzes historical trader behavior in the context of Bitcoin market sentiment (Fear vs Greed).  
It includes data preparation, exploratory analysis, behavioral segmentation, a predictive model for next-day profitability, and trader clustering.

Datasets used:
1. **Bitcoin Market Sentiment (Fear/Greed)** – `fear_greed_index.csv`  : https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing
2. **Historical Trader Data (Hyperliquid)** – `historical_data.csv`   : https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing
 
## Overview
Analyzing trader behavior with Bitcoin Fear/Greed sentiment. Includes:
- Data preparation
- Exploratory analysis
- Trader segmentation
- Predictive modeling (next-day PnL bucket)
- Behavioral clustering
---

## Setup

1. Clone the repository:

```bash
git clone https://github.com/khaja1233/TraderSentimentAnalysis.git

**#Install Dependencies**:
pip install pandas numpy matplotlib seaborn scikit-learn

**How to Run**

Open trader_sentiment_analysis.ipynb in Google Colab or Jupyter Notebook.

Run all cells sequentially.

Charts are displayed inline and saved in outputs/ folder.

**Outputs**

Charts: saved in outputs/ folder

Tables: inline in notebook

Predictive model evaluation (classification report)

Behavioral cluster profiles
