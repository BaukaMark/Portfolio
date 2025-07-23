# SQL Block — Customer Transaction Analysis

This folder contains all SQL-based tasks for the Data Analytics Final Project.  
The goal was to analyze customer purchase behavior over a 1-year period using SQL.

## Tasks Included

1. **Identify clients with continuous transaction history**  
   - Monthly activity check (no gaps) from June 2015 to June 2016  
   - Calculate average check, monthly spend, and total operations per client

2. **Monthly metrics breakdown**  
   - Average check per month  
   - Avg number of operations  
   - Avg number of active clients  
   - Operation and revenue shares

3. **Gender distribution by month**  
   - M/F/NA ratio per month and their share in spend

4. **Age segmentation analysis**  
   - Age groups (10-year intervals + NA)  
   - Total and quarterly breakdown of operations and spend

##  Files

- `SQL_Final_Project.ipynb` — all SQL queries and results (executed in Jupyter)
- `sql_queries.sql` — clean SQL code used in notebook
- `customer_info.xlsx` — client demographic data
- `transactions_info.xlsx` — transaction history for 12 months

## Tools

- SQLite
- Jupyter Notebook (via sqlite3 + pandas)
