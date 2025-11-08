Trading Behavior and Market Sentiment Analysis

Author: Tanishka Sharma
Project Type: Data Science Assignment — Web3 Trading Team
Tools Used: Google Colab, GitHub

Project Overview

This project explores how market sentiment, measured through the Fear and Greed Index, affects trader behavior and performance. By combining real trader data with daily sentiment values, the analysis studies how emotional market phases like Fear and Greed influence trade size, risk-taking, and profitability.

The goal is to understand whether traders behave differently under changing market conditions and how emotions impact trading outcomes.

Datasets Used

Trader Data (historical_data.csv)
Contains information about trades such as account IDs, trade size in USD, and profit or loss. It helps analyze trader performance and activity levels.

Market Sentiment Data (fear_greed_index.csv)
Represents the emotional state of the market, labeled as Extreme Fear, Fear, Neutral, Greed, or Extreme Greed. This data helps link market mood with trading behavior.

Both datasets were merged using the date column so that each trade could be analyzed along with the corresponding market sentiment of that day.

https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjV
s/view?usp=sharing #Historical Trader Data

Project Steps

Data Cleaning: Removed duplicates, renamed columns, handled missing values, and converted timestamps into a readable date format.
Data Merging: Combined both datasets on the date column to connect each trade with the market sentiment of that day.
Feature Preparation: Created a sentiment column and used one-hot encoding to prepare the data for analysis.
Exploratory Data Analysis (EDA): Calculated averages, compared profits and trade sizes across sentiment states, and visualized results using Seaborn and Matplotlib.
Insights Generation: Highlighted how Fear and Greed phases affect trader decisions and performance.

Key Findings

Traders earned higher profits during Greed phases but also faced greater risk and volatility.

During Fear, traders preferred smaller and safer trades, showing a cautious mindset.

A small number of accounts generated most of the overall profit, indicating that experience and strategy play a major role.

Trade size and profit had a mild positive relationship, meaning larger trades often resulted in higher profits or losses.

The market experienced more Fear days than Greed, suggesting a generally cautious environment.

Visual Outputs

All charts and visualizations are available in the outputs folder.

Visualization	Description

	Average profit comparison between Fear and Greed

	Top 10 trader accounts ranked by profit

	Correlation between trading variables

	Profit distribution across sentiment phases
Tools and Technologies

Python

Pandas, NumPy, Seaborn, Matplotlib

Google Colab for coding and visualization

GitHub for version control and documentation

How to Run the Notebook

Open the notebook in Google Colab: Open notebook_1.ipynb in Colab

Upload the CSV files or mount your Google Drive.

Run all cells in order to reproduce the analysis and visualizations.

Summary of Insights

This project shows that emotions play a major role in trading. When the market is in a Greed phase, traders take larger risks and trade more actively, which can lead to higher profits but also more losses. During Fear, traders become more conservative, preferring smaller and safer trades.

Understanding these behavioral patterns can help traders and analysts make smarter, emotion-aware decisions and improve their strategies.
