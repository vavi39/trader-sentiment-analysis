# Trader Behavior Insights Report
## Objective
Analyze the relationship between trader performance and Bitcoin market sentiment to derive actionable trading strategies.
## Methodology
- Cleaned and merged Fear/Greed and Historical Trader datasets.
- Performed EDA to visualize trends in Closed PnL, trade volume, and approximated leverage.
- Conducted statistical tests (t-test), clustering (KMeans), and predictive modeling (Random Forest).
- Created an interactive Plotly dashboard for stakeholder insights.
## Key Findings
- **Profitability**: Highest average PnL (67.89) in Extreme Greed periods.
- **Trade Volume**: Highest volume ($483,324,789.79) in Fear periods.
- **Leverage Risk**: High-leverage trades in Greed periods lead to losses.
- **Cluster Insights**: Cluster 1.0 has the best performance (avg PnL: 191.20).
- **Predictive Model**: Size USD is the top predictor (Importance: 0.25).
- **Note**: Fear/Greed dates were shifted from 2018 to 2024 to align with Trader data for analysis, as sample data showed a mismatch.
## Trading Strategies
- Increase trade size during Greed periods to capitalize on bullish trends.
- Reduce leverage in Fear periods to minimize losses.
- Monitor 7-day sentiment moving average for trend reversals.
- Emulate strategies of high-performing trader clusters.
## Dashboard
The interactive dashboard (`trader_sentiment_dashboard.html`) visualizes sentiment trends, PnL, volume, leverage, and trader clusters. Open in a browser for exploration.