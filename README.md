**Project Overview:

Title: Cross-Market Analysis: Crypto, Oil & Stocks with SQL and Streamlit. Domain: Financial Analytics / Business Intelligence (BI).**
The core objective of this project is to build an analytics platform to determine if cryptocurrency behaves like "digital gold" (correlated with traditional assets) or if it is a completely different asset class. You will achieve this by comparing the performance of top cryptocurrencies against Oil (WTI benchmark) and global stock indices (S&P 500, NASDAQ, NIFTY) over the past few years.
Key Objectives & Use Cases
The project aims to facilitate several real-world business scenarios:
Investment Research: Analyzing whether Bitcoin moves with or against oil and stock markets.
Risk Management: Comparing the volatility of crypto against traditional assets.
Macro-Economic Analysis: Studying the impact of global events on crypto prices.
Trading Strategies: Testing hypotheses such as "hedge with S&P during crypto downturns".
Technical Workflow
The project follows a standard ETL (Extract, Transform, Load) and visualization workflow:

1. Data Collection (ETL)
You are required to gather data from three specific sources:
Cryptocurrency: Use the CoinGecko API to fetch metadata for all coins and historical daily prices for the top 3 coins (based on market cap) for one year.
Oil Prices: Download WTI Crude daily prices (Jan 2020 – Jan 2026) from a specific GitHub dataset.
Stock Prices: Use the Yahoo Finance API to download historical data (Jan 2020 – Sept 2025) for tickers like ^GSPC (S&P 500) and ^NSEI (NIFTY).

2. Database Design (SQL)
You must design a relational database (using MySQL, PostgreSQL, or SQLite) containing four main tables:
cryptocurrencies: Stores metadata like symbol, name, market cap, and supply.
crypto_prices: Stores daily price history linked to the coin ID.
oil_prices: Stores daily WTI crude oil prices.
stock_prices: Stores daily open, high, low, close, and volume data for stock indices.

3. Analytics (SQL Queries)
You will write SQL queries to extract insights, including:
Single-Market Analysis: Finding ATH (All-Time Highs), volatility calculations, and moving averages.
Cross-Market Joins: Complex queries to compare assets, such as correlating Bitcoin closing prices with Crude Oil on the same dates or checking if Bitcoin moves with the S&P 500.

4. Streamlit Dashboard
The final deliverable is an interactive Streamlit application with three navigation pages:
Page 1: Market Overview: Allows users to filter by date range and view a "Daily Market Snapshot" comparing Bitcoin, Oil, and Stock indices side-by-side.
Page 2: SQL Query Runner: An interactive interface where users select predefined SQL queries (e.g., "Top 3 Cryptocurrencies") and view the results in a table format.
Page 3: Top 5 Crypto Analysis: A deep-dive page allowing users to select a specific coin and view its daily price trend via line charts and tables.

Project Requirements
Timeline: 14 days from assignment.


Tech Stack: Python, SQL, Streamlit, Pandas, and API integration.
