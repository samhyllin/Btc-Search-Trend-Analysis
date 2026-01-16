# BTC-Search-Trend-Analysis

## Background
This project explores Bitcoin’s price trends alongside public interest over time. Using historical daily Bitcoin prices and Google search trend data, the goal is to identify how news attention correlates with price movements. The analysis focuses on trends, peaks in search volume, and how investor or public interest reflects in Bitcoin price changes. Insights from this study help understand market sentiment and the relationship between cryptocurrency popularity and market performance.

## Project Structure
```
│
├── • data
│ ├── • Bitcoin Search Trend.csv
│ └── • Daily Bitcoin Price.csv
│
├── • notebooks
│ └── • btc_analysis.ipynb
│
├── • images
│ ├── • btc_yearly_price_volume.png
│ ├── • btc_yearly_search.png
│ └── • btc_price_vs_search.png
│
└── • README.md
```
## Data Cleaning
```
• Checked for missing values in both datasets and removed rows with NaNs.
• Converted date columns from object/string to datetime format for accurate time-based analysis.
• Resampled daily price data to monthly and yearly aggregates to analyze trends over time.
• Created a year column for grouping and aggregation.
• Ensured data types were consistent for calculations and visualizations.
```

## Analysis
```
• Calculated yearly average Bitcoin prices and trading volumes.
• Aggregated Bitcoin search trends by year to track changes in public interest.
• Compared monthly search trends with monthly price movements to examine correlation.
• Identified peak years for Bitcoin attention, such as late 2017–2018, where both price and search activity spiked.
• Examined cases where price movements did not align with search spikes to understand market maturity effects.
```

## Visualization
```
• Used Plotly for interactive bar and line charts to highlight yearly trends in price, volume, and search interest.
• Created a dual-axis chart to compare monthly Bitcoin price with Google search trends.
• Used Matplotlib for static charts to present price versus search trends with clear styling, axes, and labels.
• Visualizations reveal patterns such as hype periods, seasonal attention spikes, and gradual increase in Bitcoin awareness over the years.
• Charts provide actionable insights into the relationship between public interest and Bitcoin price movements.
```
## Project Overview
This project analyzes Bitcoin’s historical price data alongside public search interest to uncover trends and correlations. By combining daily price and trading volume data with Google search trends, the analysis explores how public attention relates to Bitcoin’s market movements. The goal is to identify hype periods, long-term trends, and how investor interest is reflected in search behavior.

## Tool Used
```
• Python for data analysis and preprocessing
• Pandas for data cleaning, aggregation, and transformation
• Matplotlib for static visualizations
• Plotly for interactive charts and dual-axis plots
• Jupyter Notebook for exploratory analysis and reporting
```
## Key Insights
```
• Bitcoin price and search interest often spike simultaneously during hype periods, such as late 2017–2018.
• Early price surges do not always correspond with large search spikes once Bitcoin became widely known (e.g., 2019).
• Yearly aggregation reveals long-term trends in price and public interest.
• Trading volume grows alongside price, indicating increasing market activity during major price movements.
• Dual-axis visualizations show that public interest can act as a leading indicator during periods of rapid price growth.
```
## Executive Summary
This project investigates the relationship between Bitcoin’s market performance and public interest over time. Using historical daily Bitcoin prices, trading volumes, and Google search trends, the analysis highlights how spikes in public attention often coincide with major price movements.

Key findings include:
```
• Late 2017–2018 saw massive increases in both Bitcoin price and search activity, reflecting heightened public interest during hype periods.
• Early surges in price did not always generate proportional search spikes, suggesting that public awareness and market maturity influence search behavior.
• Yearly and monthly aggregations reveal long-term trends in price, volume, and search interest, smoothing out short-term fluctuations.
• Dual-axis visualizations demonstrate that search trends can sometimes act as a leading indicator during rapid price movements, providing insight into market sentiment.
```
The project provides actionable insights into Bitcoin’s historical trends and public perception, illustrating how interest and price interact over time. It combines data cleaning, aggregation, and both interactive and static visualizations to deliver a clear analytical narrative.
