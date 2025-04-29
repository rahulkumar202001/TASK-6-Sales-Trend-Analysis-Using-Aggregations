Task 6: Sales Trend Analysis Using SQL

Objective
Analyze monthly revenue and order volume using SQL aggregation functions.

Tools Used
 MySQL

SQL Logic
- Used `EXTRACT` or `strftime` to group by month/year.
- Aggregated revenue using `SUM(amount)`
- Counted unique orders using `COUNT(DISTINCT order_id)`
- Sorted using `ORDER BY`

Result
(Screenshot or sample result table here)

Summary:
Analyzed monthly revenue and order volume using SQL aggregation. 
Used SUM(amount) for revenue, COUNT(DISTINCT order_id) for volume, and grouped by YEAR(order_date) and MONTH(order_date).
Also retrieved top 3 months by sales using DATE_FORMAT(order_date, '%Y-%m'). 
Submitted SQL script, results, and a README via GitHub.
