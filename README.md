# 🍽️ Restaurant Data Analysis using SQL
 
A hands-on SQL practice project built on restaurant data. The goal is to practise core SQL concepts and answer real business questions, such as which dishes sell best, who the top customers are, and how revenue changes over time.
 
---
 
## 📌 Project Overview
 
This project uses two related tables, **Customer** and **Food Sales**, to practise writing SQL queries that turn raw data into useful business insights.
 
**Skills practised:**
- Data aggregation (`SUM`, `COUNT`, `AVG`, `MIN`, `MAX`, `GROUP BY`, `HAVING`)
- Joins (`INNER JOIN`, `LEFT JOIN`)
- Common Table Expressions (CTEs)
- Window functions (`ROW_NUMBER`, `RANK`, `DENSE_RANK`, running totals)
- Filtering, sorting and basic analytical questions
---
 
## 🗂️ Dataset
 
The database has two tables.
 
### 1. `customer`
| Column | Description |
|---|---|
| `customer_id` | Unique ID for each customer (Primary Key) |
| `customer_name` | Name of the customer |
| `city` | City of the customer |
| `...` | *(add your other columns)* |
 
### 2. `food_sales`
| Column | Description |
|---|---|
| `order_id` | Unique ID for each order (Primary Key) |
| `customer_id` | Links to the `customer` table (Foreign Key) |
| `food_item` | Name of the dish ordered |
| `category` | Food category |
| `quantity` | Number of units ordered |
| `price` | Price per unit |
| `order_date` | Date of the order |
| `...` | *(add your other columns)* |
 
**Relationship:** `customer.customer_id` → `food_sales.customer_id` (one customer can place many orders)
 
> 📝 Update the column names above to match your actual tables.
 
---
 
