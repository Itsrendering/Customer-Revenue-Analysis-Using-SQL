# Customer-Revenue-Analysis-Using-SQL
This project is designed to show:  clean, readable SQL  business thinking  clear communication (soft skills)  junior-level readiness


Project Overview

This project analyzes a small sales database to understand customer behavior and revenue trends. The goal is to provide insights that could help a sales team make decisions, such as which customers to focus on and how revenue changes over time.

The project shows basic SQL skills and business thinking that a junior analyst would use in real-world scenarios.

Dataset

Two tables are used:

customers
Column	Type
customer_id	INT
first_name	VARCHAR
last_name	VARCHAR
signup_date	DATE
orders
Column	Type
order_id	INT
customer_id	INT
order_date	DATE
order_total	DECIMAL

The data is simulated to reflect a realistic e-commerce scenario.

Approach

Used aggregation functions like SUM and COUNT

Grouped data by customer and month to analyze revenue

Used CASE statements to classify customers as new or returning

Focused on getting meaningful insights rather than just running queries
