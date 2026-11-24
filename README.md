**Mini ETL Project: MySQL + Python**

A hands-on ETL practice project built while learning data analytics. It uses three datasets (India housing prices, NYC Airbnb listings, Superstore sales) and moves data between MySQL and Python.

## What this project does
- Connects Python to MySQL using SQLAlchemy and PyMySQL
- Extracts tables into pandas DataFrames
- Checks data quality: null values, duplicates, data types, summary statistics
- Combines two Superstore tables into one 19,388-row dataset
- Practices left, right, and inner merges on orders and customers
- Loads the merged results back into MySQL as new tables

## Files
- `etl_practice_17.11.26.ipynb`: Python notebook with the full ETL steps
- `etl_practice_17.11.26_sql.sql`: SQL script for creating the database and checking the loaded tables

## Tools used
Python, pandas, SQLAlchemy, PyMySQL, MySQL

## Key learning
All three merges returned the same row count (19,388) because every order had a matching customer, which helped me understand how join types behave.

