# Trader Sentiment Analysis

## 📌 Problem Statement
Explore the relationship between trader performance and Bitcoin market sentiment (Fear/Greed Index) to derive actionable insights.

## 🛠️ Approach
- Merged Fear & Greed Index with historical trader data
- Analyzed trade performance across sentiment classifications
- Applied statistical testing (T-test), clustering (KMeans), and Random Forest modeling
- Built interactive Plotly dashboard for exploration

## 📊 Key Findings
- Traders are most profitable during **Greed** phases.
- Trade volume increases during **Extreme Greed**.
- **High leverage trades during Fear periods lead to more losses**.
- **Leverage and sentiment value** are top predictors of profitability.
- Cluster analysis reveals distinct trading behaviors with varying success.

## 📂 Included Files
- `trader_sentiment_analysis.ipynb` - Main notebook with outputs
- `trading_insights.txt` - Auto-generated insights
- `report.md` - Written report
- `sentiment_ma.png` - Sentiment trend plot
- `feature_importance.png` - Feature importance from Random Forest
- `trader_sentiment_dashboard.html` - Interactive dashboard

## ▶️ How to Run
1. Clone the repo or open the `.ipynb` in [Google Colab](https://colab.research.google.com/)
2. Install required packages (e.g., `pandas`, `scikit-learn`, `plotly`, `matplotlib`, `seaborn`)
3. Run all cells top to bottom

## 🙋‍♂️ Author
Avi Verma
