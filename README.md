# 🗄️ SQL Practice

Practice SQL queries as part of my Data Analytics course.

## Topics Covered
- SELECT, WHERE, ORDER BY
- GROUP BY and aggregate functions (SUM, COUNT, AVG)
- JOINs (INNER, LEFT)
- Subqueries
- Filtering and sorting data

## Sample Queries I'm Learning

-- Total sales by category
SELECT category, SUM(sales) AS total_sales
FROM orders
GROUP BY category
ORDER BY total_sales DESC;

-- Top 5 customers
SELECT customer_name, COUNT(order_id) AS total_orders
FROM orders
GROUP BY customer_name
ORDER BY total_orders DESC
LIMIT 5;

## Tools
- MySQL / SQL Server
- Practicing on sample datasets
