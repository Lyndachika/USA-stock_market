
US Stock Market SQL Analysis Project

This project utilizes a stock market dataset from Kaggle, which has been cleaned and analyzed using MySQL. It demonstrates real-world data analysis skills, using over 10 SQL queries.

File Included 
stock_market schema
cleaned_stock_market_data.csv  
Stock_Market_Queries.sql     
                  

 Dataset Overview

- Source: [Kaggle - US Stock Market Data](https://www.kaggle.com/)
- Covers key financial data including:
  - Commodities (Gold, Crude Oil, Natural Gas)
  - Cryptocurrencies (Bitcoin, Ethereum)
  - Major Stocks (Apple, Tesla, Microsoft, etc.)
  - Indexes (S&P 500, NASDAQ 100)
- Fields include: price, volume, and trading date


 Data Cleaning Summary

The CSV file was cleaned using Excel
- Converted all date values to YYYY-MM-DD format
- Removed commas from numeric values (e.g., 43,081.40 → 43081.40)
- Ensured numeric columns were stored as DECIMAL or BIGINT



SQL Concepts Practiced

Aggregate functions (AVG, MAX, MIN, SUM)  
Filtering (WHERE, LIKE)  
Sorting (ORDER BY)  
Grouping (GROUP BY, WEEK(), YEAR())    
Trend analysis using dates  
Volume and price comparisons
