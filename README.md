Food Delivery Analytics Project (PostgreSQL)

Project Overview
This project is a food delivery analytics system built using PostgreSQL. It simulates a real-world platform similar to Zomato/Swiggy and focuses on data modeling and SQL-based analysis.

The main objective is to analyze customer behavior, restaurant performance, delivery efficiency, and revenue trends using structured SQL queries.

---

Database Design

The project is built using a relational schema with five tables:

* customers: stores customer details such as customer_id, name, and city
* restaurants: stores restaurant information including cuisine type and location
* orders: contains order-level data with customer_id, restaurant_id, order_date, and status
* order_items: contains item-level details of each order including price and quantity
* deliveries: stores delivery details such as delivery_time and rating

---

Dataset Summary

* Customers: 100 records
* Restaurants: 50 records
* Orders: 200 records
* Order Items: 400 records
* Deliveries: 200 records

---

Key Analysis Performed

Customer Analysis

* Identified top customers based on total spending
* Analyzed order frequency patterns

Restaurant Analysis

* Found top-performing restaurants based on orders and revenue
* Compared performance across cuisines

City-Level Analysis

* Measured order distribution across different cities
* Identified high-demand locations

Revenue Analysis

* Calculated total revenue and restaurant-wise contribution
* Identified top revenue-generating restaurants

Delivery Analysis

* Calculated average delivery time
* Classified deliveries into Fast, Medium, and Slow categories
* Analyzed customer ratings distribution

Customer Behavior Analysis

* Studied repeat ordering patterns using LAG function
* Calculated customer lifetime value (CLV)

Trend Analysis

* Monthly order trends
* Running revenue growth over time

---

SQL Concepts Used

* Basic SQL operations: SELECT, WHERE, ORDER BY, GROUP BY
* Joins: INNER JOIN across multiple tables
* Aggregations: SUM, COUNT, AVG
* Conditional logic: CASE WHEN
* Subqueries and CTE (WITH clause)
* Window functions:

  * RANK()
  * DENSE_RANK()
  * LAG()
  * OVER (PARTITION BY / ORDER BY)

---

Key Learnings

* Designed a relational database from scratch
* Generated and managed structured datasets
* Applied SQL for real-world business analysis
* Used advanced SQL functions for insights
* Converted raw data into meaningful business metrics

---

Tools Used

PostgreSQL


---

Project Outcome

* Built an end-to-end data analytics project
* Simulated real-world food delivery system
* Demonstrated strong SQL and analytical thinking
* Created portfolio-ready project for data analyst roles

