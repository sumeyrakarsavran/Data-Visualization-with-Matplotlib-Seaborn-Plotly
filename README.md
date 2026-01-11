# Data Analysis & Visualization Projects Repository

This repository contains numerous hands-on projects covering data analysis with Python, exploratory data analysis (EDA), data cleaning, feature engineering, and advanced data visualization.

The work uses real-world datasets including financial data, Google search trends, and time-series data. The goal is to teach core data science concepts and provide professional examples of analysis and visualization.

<img width="898" height="450" alt="newplot2" src="https://github.com/user-attachments/assets/a7d41798-8c9a-4307-9c39-a5f296e30dfc" />

<img width="898" height="450" alt="newplot" src="https://github.com/user-attachments/assets/99ff6d24-7609-498a-a3fb-dbd802c24fd5" />

<img width="898" height="450" alt="newplot3" src="https://github.com/user-attachments/assets/fa486527-8845-4753-adea-95cebaa29aad" />

<img width="610" height="389" alt="7ad4c418-d26c-4cf6-9b49-f3967ac09cbe" src="https://github.com/user-attachments/assets/33c1279c-5968-4326-beff-4daf5f5619c1" />

<img width="552" height="405" alt="8163bb97-46c1-4abc-ada8-8ccee510bd17" src="https://github.com/user-attachments/assets/fcdf2a48-799e-4839-a10a-7e8996d3b980" />

## Summary

This repo includes projects in the following main areas:

- Exploratory Data Analysis (EDA): Data inspection and summary statistics
- Data Cleaning & Imputation: Handling missing values and cleaning pipelines
- Feature Engineering: Creating meaningful features from raw data
- Matplotlib & Seaborn Visualizations: Static plotting and styling techniques
- Financial Data Analysis (yfinance): Stock data retrieval and analysis
- Google Trends Analysis (pytrends): Search trend extraction and comparison
- Time Series Analysis: Trend and seasonality exploration
- Advanced Charts: Polar, 3D, Area, Funnel, Sunburst, and other complex plots
- Socioeconomic & Demographic Analyses

## 1. Exploratory Data Analysis (EDA)

Common EDA steps applied:

- head(), tail(), sample()
- shape, info()
- Statistical summary with describe()
- Missing data analysis with isnull().sum()
- Correlation analysis using corr()
- Exporting statistical outputs to Excel

Purpose: Understand the data, identify structural issues, and prepare for analysis.

## 2. Data Cleaning & Imputation

Missing-value strategies used:

- Categorical: fillna('pending')
- Numerical: mean, median, mode
- Drop columns with >20% missing values
- Remove unnecessary columns

Real-world data problems are simulated and addressed.

## 3. Feature Engineering

New meaningful features derived from time-based fields:

- From date columns: day, month, year, month name, weekday
- From time columns: hour-based analysis
- Standardizing categorical labels (e.g., RB -> Running Back, QB -> Quarter Back)

## 4. Visualizations with Matplotlib & Seaborn

Chart types demonstrated:

- Line plot, Scatter plot, Histogram, Box plot
- Heatmap (correlation), Countplot, Area chart, Stem plot
- Polar chart, 3D stem plot

Plot practices:

- Multiple subplots, figure size and DPI settings
- Use of hue, palettes, and explode
- Saving figures to files

## 5. Supermarket Sales Analysis Project

Analysis on three months of supermarket sales data:

- Branch-level sales comparisons
- Customer gender & product relationships
- Hourly product sale intensity
- Monthly and branch shopping behaviors
- Rating and customer satisfaction analysis

Techniques used: countplot, relplot, lineplot, boxplot, pie chart

## 6. Financial Data Analysis - yfinance

Library used: yfinance

Sample tickers analyzed: TSLA, AAPL, MSFT, AKBNK.IS, BAYRK.IS

Work performed:

- Fetch daily market data
- Long-term price analysis (2018-2024)
- Visualize closing prices
- Multi-stock comparisons

## 7. Google Trends Analysis - pytrends

Library used: pytrends

Analyses include:

- Programming language trends (Python, R, C++, Java, HTML)
- Popularity comparisons of political figures
- Region-based search intensity
- Time-series trend analysis

Country-level Google search trends are visualized.

## 8. Interactive Charts with Plotly

Chart types used:

- Sunburst, Bubble (scatter), Funnel
- Gapminder-style visualizations

Benefits of Plotly:

- Interactive, hover-enabled charts suitable for presentations and dashboards

## Technologies

- Python
- pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- yfinance
- pytrends
