# Semiconductor-Volume-Price-Dynamics
Data engineering, financial analytics, statistical analysis, and visualization. Supplementary tool - ChatGPT
---
<table>
<tr>
<td width="75%">

# Semiconductor Volume–Price Dynamics

### Intraday Market Microstructure Analysis Using PostgreSQL, Python, Excel, and Statistical Modeling

This project analyzes over **three years of intraday trading activity** across **19 semiconductor companies and the SOXX ETF**, using minute-level market data to investigate how trading volume influences short-term price movements and volatility.

The project was designed as an end-to-end analytical workflow, beginning with **data extraction from PostgreSQL**, followed by **data transformation, aggregation, statistical analysis, regression modeling, and visualization** to identify liquidity-driven market behavior across the semiconductor sector.

## Business Problem

Financial markets generate massive amounts of high-frequency data, yet volume is often treated as a simple indicator rather than a measurable driver of market behavior.

This study investigates:

- How trading volume impacts short-term price movement
- Whether volume–price relationships differ across semiconductor companies
- Which stocks exhibit the most predictable responses to liquidity changes
- How intraday trading patterns evolve throughout the trading day

## Dataset

- 20 Securities Analyzed
  - 19 Semiconductor Companies
  - SOXX Semiconductor ETF
- 3 Years of Historical Data (2021–2023)
- Minute-Level Market Data
- PostgreSQL Source Tables (`polygon_1m_bars`)

Key fields included:

- Open
- High
- Low
- Close
- VWAP
- Volume
- Trade Count
- Timestamp

## Technical Workflow

### Data Engineering

- Extracted market data from PostgreSQL
- Filtered and structured minute-level trading records
- Built aggregation pipelines for time-series analysis
- Generated derived volatility and price-impact metrics

### Statistical Analysis

- Correlation Analysis
- Regression Modeling
- Volume–Volatility Analysis
- Price Impact Curves
- Intraday Heatmaps

### Visualization

- Time-of-Day Heatmaps
- Volume Distribution Analysis
- Volatility Comparisons
- Price Impact Curves

## Key Findings

### No Universal Sector Pattern

Contrary to expectations, semiconductor stocks do not exhibit a common volume–price relationship. Liquidity effects vary significantly across companies.

### Most Predictable Stocks

The strongest volume-driven relationships were observed in:

- NVIDIA (NVDA)
- AMD
- Micron (MU)

### ETF Behavior Differs

SOXX displayed behavior that differed substantially from individual equities, often showing negative volume–price relationships due to ETF flow mechanics.

### Intraday Liquidity Concentration

Trading activity consistently peaked:

- Immediately after market open
- Near market close

with substantially lower activity during mid-day sessions.

## Tools & Technologies

PostgreSQL • Python • Excel • Statistical Modeling • Time-Series Analytics • Regression Analysis • Data Visualization

</td>

<td width="25%" align="center">

<img src="images/postgresql.png" width="65"><br><br>
<img src="images/python.png" width="65"><br><br>
<img src="images/excel.png" width="65"><br><br>
<img src="images/statistics.png" width="65">

</td>
</tr>
</table>
