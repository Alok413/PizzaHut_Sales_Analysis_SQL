# 🍕 PizzaHut Sales Analysis Using SQL

## 📌 Project Overview

This project focuses on analyzing PizzaHut sales data using SQL to uncover meaningful business insights, identify sales trends, and evaluate product performance.

The analysis uses four relational tables to explore order patterns, revenue generation, pizza category performance, and best-selling products.

The main objective is to transform raw sales data into actionable business insights using SQL and MySQL.

## 🎯 Business Objectives

- Calculate the total number of orders placed.
- Determine the total revenue generated from pizza sales.
- Identify the highest-priced pizza.
- Find the most popular pizza size.
- Identify the top 5 most ordered pizza types.
- Analyze category-wise pizza sales.
- Understand order distribution by hour of the day.
- Calculate the average number of pizzas ordered per day.
- Identify the top 3 revenue-generating pizza types.
- Calculate the percentage contribution of each pizza category to total revenue.
- Analyze cumulative revenue over time.
- Find the top 3 revenue-generating pizzas within each category.

## 🗂️ Dataset Description

The project consists of four relational tables:

| Table Name | Description |
|---|---|
| `orders` | Contains order IDs, order dates, and order times. |
| `order_details` | Contains order details, pizza IDs, and quantities. |
| `pizzas` | Contains pizza IDs, sizes, and prices. |
| `pizza_types` | Contains pizza names, categories, and ingredients. |

## 🛠️ Tools & Technologies

- **SQL** – Data querying and analysis
- **MySQL** – Relational database management
- **MySQL Workbench** – SQL development and query execution
- **GitHub** – Project documentation and version control

## 📊 Key Business Insights

Based on the SQL analysis, the following insights were identified:

1. **Total Orders:** A total of 21,350 orders were placed.
2. **Total Revenue:** Approximately $817,860.05 in revenue was generated.
3. **Highest-Priced Pizza:** The Greek Pizza was the highest-priced pizza at $35.95.
4. **Most Popular Pizza Size:** Large (L) was the most frequently ordered size, with 18,526 orders.
5. **Best-Selling Pizza:** The Classic Deluxe Pizza ranked first in quantity sold, with 2,453 pizzas.
6. **Category Performance:** Classic pizzas contributed the highest percentage of revenue at 26.91%.
7. **Top Revenue-Generating Pizza:** The Thai Chicken Pizza generated the highest revenue among individual pizza types, approximately $43,434.25.

## 🧠 SQL Concepts Applied

The following SQL concepts were used throughout the project:

- SELECT, WHERE and ORDER BY
- Aggregate Functions (SUM, COUNT, AVG)
- GROUP BY and HAVING
- INNER JOIN
- Subqueries
- Window Functions (RANK and SUM OVER)
- Date and Time Functions
- Revenue and Percentage Calculations

## 📁 Repository Structure

```text
PizzaHut-Sales-Analysis-SQL/
│
├── data/
│   ├── orders.csv
│   ├── order_details.csv
│   ├── pizzas.csv
│   └── pizza_types.csv
│
├── report/
│   └── PizzaHut Sales Analysis.pdf
│
└── README.md