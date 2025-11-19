# Self-Updating-Market-Model-with-Bloomberg-Terminal

# Self-Updating Market Dashboard with Quantitative Models

## Overview
Automated market analytics platform integrating Bloomberg Terminal data 
with quantitative models for real-time portfolio insights.

## Key Features
- Real-time data ingestion via Bloomberg API
- 3 quantitative models: [momentum, mean-reversion, factor]
- Interactive dashboard with 10+ visualization types
- Automated daily updates with anomaly detection
- Risk management and attribution analytics

## Tech Stack
- Data: Bloomberg API (Python), MySQL
- Models: scikit-learn, statsmodels, pandas
- Dashboard: Streamlit/Plotly Dash
- Automation: Apache Airflow / cron
- Deployment: Docker, AWS/GCP

## Performance Metrics
- Sharpe Ratio: 1.2 (vs S&P500: 0.8)
- Max Drawdown: -8% (vs S&P500: -15%)
- Hit Rate: 58%
- Uptime: 99.5% over 3 months

## Architecture
[Include diagram showing: Bloomberg → ETL → Database → Models → Dashboard]

## Limitations & Future Work
- Currently limited to equities (expanding to multi-asset)
- Assumes no transaction costs in backtest
- Daily frequency (working on intraday)
