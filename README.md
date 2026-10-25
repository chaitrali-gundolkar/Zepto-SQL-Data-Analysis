# Zepto-SQL-Data-Analysis
Zepto product data analysis using SQL and PostgreSQL
# Zepto Data Analysis Using SQL

## Project Overview
This project focuses on analyzing Zepto product data using PostgreSQL. The goal is to explore product availability, pricing, discounts, and product categories using SQL queries.

## Objectives
- Explore the Zepto product dataset.
- Identify and check missing values.
- Analyze product availability (in stock vs. out of stock).
- Identify product names associated with multiple SKU records.
- Analyze product discounts and pricing.
- Estimate available inventory value by product category.
- Identify products with high MRP and low discounts.

## Tools & Technologies
- PostgreSQL
- pgAdmin
- SQL
- CSV dataset

## Dataset Description
The dataset contains product-related information, including:
- SKU ID
- Product category
- Product name
- Maximum Retail Price (MRP)
- Discount percentage
- Available quantity
- Discounted selling price
- Product weight in grams
- Stock status
- Quantity

## SQL Concepts Used
- SELECT
- WHERE
- DISTINCT
- COUNT()
- GROUP BY
- HAVING
- ORDER BY
- LIMIT
- Aggregate functions
- UPDATE
- DELETE
- CREATE TABLE

## Business Questions Answered
1. How many records are present in the dataset?
2. Are there any missing values in the product data?
3. What product categories are available?
4. How many product records are in stock and out of stock?
5. Which product names appear multiple times?
6. Which products have the highest discount percentages?
7. Which high-MRP products are out of stock?
8. What is the estimated available inventory value for each category?
9. Which products have an MRP greater than ₹500 and a discount below 10%?
10. Which categories have the highest average discount percentage?

## Project Files
- `zepto_analysis.sql` — SQL queries used for data exploration, cleaning, and analysis.
- `zepto_v1_utf8.csv` — Dataset used in the project.

## Key Learnings
- Practiced writing SQL queries to answer business questions.
- Learned to group and count product records using aggregate functions.
- Explored product availability, pricing, and discount patterns.
- Practiced basic data cleaning using SQL.

## Important Note
The category-level calculation using discounted selling price multiplied by available quantity estimates the value of available inventory. It does not represent actual sales revenue unless actual sales data is available.

## Author
Chaitrali Gundolkar
