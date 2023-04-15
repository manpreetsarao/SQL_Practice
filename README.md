# SQL_Practice
Complex queries
This respostery is for qriting the cokmplex queries for practice.
To select top 3 profitable drugs from cvs.
SELECT drug, total_sales-cogs as total_profit 
FROM pharmacy_sales order by total_profit desc limit 3;
