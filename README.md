# data-analytics-TASK-4
📌 Objective

The original task was to use SQL queries for data analysis.
Here, I replicated the same process using Excel (with Power Query, Pivot Tables, and formulas) to demonstrate SQL-like operations.

📂 Files Included

SQL_in_Excel_Workflow.xlsx → Contains:

Customers – customer information

Orders – order transactions

Products – product catalog

Order_Details – mapping of orders to products

Customer_Orders_Join – result of INNER JOIN (Customers + Orders)

Total_Revenue – grouped results showing total revenue per customer (like GROUP BY)

ARPU – Average Revenue Per User (like AVG() in SQL)

🔄 SQL Concepts → Excel Implementation
SQL Concept	Excel Equivalent
SELECT columns	Selecting columns in Excel / Power Query
WHERE (filter)	Filters in Excel or Power Query
ORDER BY	Sort feature in Excel
GROUP BY + SUM()	Pivot Tables / Group By in Power Query
JOIN (INNER)	Power Query → Merge Queries / VLOOKUP/XLOOKUP
Subqueries	Nested formulas or helper sheets
Views	Separate sheets / Saved Queries
Indexes	Converting ranges to Tables (Insert → Table)
📊 Example Outputs

INNER JOIN – Customers + Orders merged into Customer_Orders_Join sheet.

Total Revenue per Customer – Total_Revenue sheet (GROUP BY SUM).

ARPU (Average Revenue Per User) – ARPU sheet.

Pivot Tables can be created in Excel for country-wise revenue or customer spending analysis.
