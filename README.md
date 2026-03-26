# Trader-Sentiment-Analysis
Analyze how market sentiment (Fear/Greed) relates to trader behavior and performance on Hyperliquid.

# Trader Performance vs Market Sentiment Analysis

## Objective
Analyze how market sentiment (Fear/Greed) affects trader behavior and performance.

---

## Methodology

1. Data Preparation  
- Converted timestamps into datetime format  
- Aligned datasets at daily level  

2. Feature Engineering  
- Daily PnL per trader  
- Win rate  
- Average trade size  
- Number of trades  

3. Data Merging  
- Combined trading metrics with sentiment data  

4. Analysis  
- Compared performance across sentiment  
- Studied behavioral changes  
- Performed segmentation  

---

## Key Insights

1. Traders perform worse during Fear periods, with lower PnL and higher volatility.  

2. Traders increase trade frequency and position size during Greed, indicating higher risk-taking.  

3. High-frequency traders tend to underperform, suggesting overtrading reduces profitability.  

---

## Strategy Recommendations

1. Reduce risk during Fear periods by lowering position size and trading frequency.  

2. Avoid overtrading during Greed periods and limit the number of trades.  

3. Focus on consistency and disciplined strategies rather than frequent trading.  

---

## How to Run

1. Install dependencies:
   pip install pandas matplotlib seaborn

2. Run the notebook:
   jupyter notebook
   Google Colab


