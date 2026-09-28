# Customer Shopping Behavior Analysis

## 📌 Project Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories.

The objective is to identify spending patterns, purchasing preferences, subscription behavior, and customer segments to generate actionable business insights.

The project follows an end-to-end data analytics workflow using Python, SQL, PostgreSQL, and Power BI.

## 📂 Dataset

**Dataset:** Customer Shopping Behavior
**Records:** 3,900
**Columns:** 18
**Missing Values:** 37 missing values in `review_rating`

### Key Features

* **Customer Demographics:** Age, gender, location, subscription status
* **Purchase Details:** Item purchased, category, purchase amount, season, size, color
* **Shopping Behavior:** Discount applied, previous purchases, purchase frequency, review rating, shipping type

## 🛠️ Tools & Technologies

| Tool             | Purpose                                |
| ---------------- | -------------------------------------- |
| Python           | Data processing and analysis           |
| Pandas           | Data cleaning and manipulation         |
| Jupyter Notebook | Exploratory analysis and documentation |
| PostgreSQL       | Database storage and analysis          |
| SQL              | Business analysis and querying         |
| Power BI         | Interactive dashboard                  |
| Gamma            | Business presentation                  |

## 🔄 Project Workflow

### 1. Data Loading

* Imported the dataset using Pandas.
* Examined dataset structure, data types, and summary statistics.

### 2. Exploratory Data Analysis

* Analyzed customer demographics and purchasing patterns.
* Examined purchase amounts and product categories.
* Identified missing values and data quality issues.

### 3. Data Cleaning & Feature Engineering

* Handled missing review ratings using the median rating of each product category.
* Standardized column names using `snake_case`.
* Created an `age_group` column.
* Created a `purchase_frequency_days` column.
* Removed the redundant `promo_code_used` column.
* Prepared the cleaned dataset for SQL analysis.

### 4. SQL Analysis

Loaded the cleaned dataset into PostgreSQL and used SQL to answer key business questions, including:

* Revenue comparison by gender
* High-spending customers who used discounts
* Top 5 products by average review rating
* Standard vs. Express shipping purchase amounts
* Subscriber vs. non-subscriber spending and revenue
* Products with the highest percentage of discounted purchases
* New, Returning, and Loyal customer segmentation
* Top 3 most-purchased products in each category
* Relationship between repeat purchases and subscription status
* Revenue contribution by age group

### 5. Power BI Dashboard

Built an interactive dashboard to visualize:

* Customer spending behavior
* Revenue trends
* Product performance
* Subscription patterns
* Customer segments
* Purchasing preferences

## 📊 Dashboard

<img width="614" height="335" alt="dashboard" src="https://github.com/user-attachments/assets/2fd8856e-8361-4930-b556-b8656118aed2" />


## 📈 Business Insights & Recommendations

The analysis identified opportunities to:

* Increase subscriptions through exclusive customer benefits.
* Improve customer retention using loyalty and rewards programs.
* Optimize discount strategies while considering profitability.
* Promote highly rated and frequently purchased products.
* Develop targeted marketing campaigns based on customer segments and purchasing behavior.

## 🎯 Skills Demonstrated

* Data Cleaning & Preprocessing
* Exploratory Data Analysis
* Python & Pandas
* SQL & PostgreSQL
* Database Connectivity
* Customer Segmentation
* Power BI Dashboard Development
* Business Analysis
* Data Visualization
* Data-Driven Decision Making

## 👤 Author

**Kishan Patel**

Aspiring Data Analyst | Python | SQL | Power BI | Excel

**GitHub:** https://github.com/kishanptll
**LinkedIn:** https://www.linkedin.com/in/kishan-patell-dataanalyst/

This project was developed as part of my data analytics portfolio to demonstrate an end-to-end approach to analyzing customer shopping behavior and translating data into actionable business insights.
