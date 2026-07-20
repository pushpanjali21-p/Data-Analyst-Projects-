# TASK-3-Data-analyst
This project focuses on performing data analysis using SQL on an Ecommerce database built in MySQL. The database contains structured tables for customers, products, orders, and order items, and multiple queries were written to analyze sales and customer behavior. The work includes using SELECT statements, filtering with WHERE, sorting with ORDER BY, grouping data with GROUP BY, applying aggregate functions like SUM and AVG, implementing different types of JOINs, writing subqueries, creating views for reporting, handling NULL values, and optimizing queries using indexes. The analysis provides insights such as total revenue, average revenue per user (ARPU), top-spending customers, and revenue distribution by country, demonstrating strong foundational skills in SQL and data analysis.

## 📌 Internship: Data Analyst Internship  
## 🛠 Tool Used: MySQL  
## 📂 Database: ecommerce_sql_database  

---

## 🎯 Objective

The objective of this task is to use SQL to extract, manipulate, and analyze structured data from an Ecommerce database.  
This task demonstrates understanding of SQL fundamentals and data analysis techniques.

---

## 🗂 Database Structure

The database consists of the following tables:

1. **customers**
   - customer_id
   - name
   - email
   - country

2. **products**
   - product_id
   - product_name
   - category
   - price

3. **orders**
   - order_id
   - customer_id
   - order_date
   - total_amount

4. **order_items**
   - order_item_id
   - order_id
   - product_id
   - quantity

---

## 📊 SQL Concepts Covered

This task includes:

- ✅ SELECT statements
- ✅ WHERE conditions
- ✅ ORDER BY sorting
- ✅ GROUP BY grouping
- ✅ Aggregate Functions (SUM, AVG, COUNT)
- ✅ INNER JOIN
- ✅ LEFT JOIN
- ✅ RIGHT JOIN
- ✅ Subqueries
- ✅ Views
- ✅ Index optimization
- ✅ NULL handling using COALESCE()
- ✅ Average Revenue Per User (ARPU) calculation

---

## 🔎 Key Analysis Performed

### 1️⃣ Total Revenue
Calculated total revenue using:
```sql
SELECT SUM(total_amount) FROM orders;


