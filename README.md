# Faasos-Data-Exploration

This repository demonstrates **SQL-based data analysis** on a simulated dataset of **Faasos customer orders, drivers, and menu items**. The project focuses on exploring order patterns, roll metrics, customer preferences, and delivery performance using **MS SQL Server**.

---

## Project Overview

The dataset includes:

- **driver** – Information about drivers and their registration dates.  
- **ingredients** – List of ingredients used in the menu.  
- **rolls** – Menu items categorized as Veg or Non-Veg rolls.  
- **rolls_recipes** – Mapping of rolls to their ingredients.  
- **driver_order** – Details of each delivery, including distance, duration, and cancellations.  
- **customer_orders** – Customer orders, including modifications and extras.  

The project aims to **analyze customer ordering patterns, track delivery metrics, and evaluate menu popularity**.

---

## Key Analyses Performed

### 1. Roll & Customer Metrics
- Total rolls ordered and unique orders per customer.  
- Maximum rolls ordered in a single order.  
- Count of **Veg vs Non-Veg rolls** ordered overall and per customer.  
- Tracking orders with **modifications** (extra items or exclusions).

### 2. Driver & Delivery Metrics
- Number of **successful deliveries** by each driver.  
- Rolls delivered by each driver and cancellations handled.  
- Analysis of deliveries with **order changes** (exclusions or extras).  

### 3. Order Customization Insights
- For each customer, the number of rolls with at least **one change** vs **no changes**.  
- Rolls delivered with **both exclusions and extras** vs single modifications.  

### 4. Advanced SQL Techniques
- Use of **Common Table Expressions (CTEs)** for pre-processing and transformations.  
- Conditional logic to handle cancellations and null values.  
- Aggregations, grouping, and counting for detailed metrics.  
- Joining multiple tables to combine **customer, driver, and menu data**.  

---

## Skills Demonstrated

- **SQL & T-SQL:** CTEs, joins, conditional aggregation, counting, grouping, and handling nulls.  
- **Data Analysis:** Customer ordering behavior, menu popularity, and delivery efficiency.  
- **Problem Solving:** Translating business rules (order modifications, cancellations) into SQL queries.  
- **Database Management:** Simulating operational datasets and performing multi-table analytics.

---

## How to Use

1. **Run the SQL Script:** Open `Faasos.sql` in **SQL Server Management Studio (SSMS)** or **Azure Data Studio**.  
2. **Explore Tables:** The script creates tables and inserts sample data to simulate real-world orders and deliveries.  
3. **Execute Queries:** Review queries to analyze metrics like customer ordering patterns, delivery performance, and menu popularity.

---

## Repository Structure
  - Fassos.sql
