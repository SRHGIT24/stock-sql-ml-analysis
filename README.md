📈 Stock SQL + ML Analysis

This project combines SQL queries and Machine Learning to analyze stock market data. Using historical price datasets, we explore trends, calculate risk/return metrics, cluster stocks, and simulate portfolio allocations with Monte Carlo simulation to identify the optimal portfolio.

🚀 Project Overview

Queried raw stock CSVs using SQL within Python (pandasql) to explore average prices and filter stocks.

Engineered financial features: daily returns, moving averages (20/50-day), rolling volatility.

Applied K-Means clustering to group stocks by risk vs. return profiles.

Simulated 5,000 portfolios with different weight combinations using Monte Carlo.

Identified the optimal portfolio allocation based on the highest Sharpe Ratio (best risk-adjusted return).

🧰 Tech Stack

Language: Python 3.x

Data Access: SQL (via pandasql)

Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

Machine Learning: K-Means clustering

Simulation: Monte Carlo portfolio optimization

Environment: Jupyter Notebook (Kaggle)

📊 Why This Matters in Finance

Risk vs. Return Analysis: Investors need to balance returns with volatility. This project quantifies both.

Clustering: Groups stocks by performance patterns to simplify portfolio diversification.

Portfolio Optimization: Monte Carlo helps visualize thousands of possible allocations and pick the best one.

Hands-On SQL + ML: Demonstrates how SQL can be integrated with Python/ML for real-world financial analytics.

📂 Files

stock_analysis_sql_ml.ipynb → Main notebook with all steps (SQL queries, ML, Monte Carlo).

⚡ Quick Start

Clone this repo and open the notebook in Jupyter/Kaggle:

git clone https://github.com/SRHGIT24/stock-sql-ml-analysis.git
cd stock-sql-ml-analysis

🔮 Example Output

📌 Clusters: Stocks grouped by average return and volatility.

📌 Portfolio Frontier: Scatterplot of 5,000 simulated portfolios with risk vs. return.

📌 Optimal Portfolio: Best allocation based on maximum Sharpe Ratio.

💡 This project highlights practical financial analytics skills — blending SQL, data engineering, and ML to inform smarter investment decisions.
