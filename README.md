# Sales Data SQL Analysis

Week 2 assignment for the **Data Analyst Course (Skill Nexis)**: SQL for Data Analysis.

## Objective
Query a sample sales database to find top customers and average order values.

## Dataset
`SQL_Sales_Dataset_200_Rows` has 200 orders with these columns:
`order_id, customer_name, order_date, category, sub_category, product_name, quantity, unit_price, total_price, region`

## Tools Used
- Python (pandas, sqlite3)
- SQLite
- Google Colab

## SQL Concepts Covered
- SELECT, WHERE, GROUP BY, ORDER BY
- Aggregations: SUM, AVG, COUNT
- Subqueries
- CASE statements

## Analysis Performed
1. Top 10 customers by total spending
2. Overall summary and average order value
3. Average order value per customer
4. Average order value by category and by region
5. Orders above the overall average (subquery)
6. Order segmentation: High, Medium, Low value (CASE)
7. Monthly revenue trend

## Files
- `Week2_SQL_Analysis.ipynb`: Colab notebook with all queries and outputs
- `week2_sql_queries.sql`: all SQL queries in one file
- `SQL_Sales_Dataset_200_Rows.csv`: dataset

## Note
Each customer has only one order in this dataset, so "top customers" are ranked by their single-order value.

## Author
Alekya Merugumalla
