# Customer Shopping Behavior Analysis

## 📌 Project Overview

This project analyzes customer shopping behavior using transactional data from **3,900 purchases** across multiple product categories.

The objective is to understand customer spending patterns, purchasing preferences, subscription behavior, and customer segments to generate actionable business insights.

The project follows an end-to-end data analytics workflow, including data loading, exploratory data analysis (EDA), data cleaning, SQL-based analysis, Power BI dashboard development, and business reporting.

## 📂 Dataset

* **Dataset:** Customer Shopping Behavior
* **Total Records:** 3,900
* **Total Columns:** 18
* **Missing Values:** 37 missing values in the `review_rating` column

### Key Features

* **Customer Demographics:** Age, gender, location, subscription status
* **Purchase Details:** Item purchased, category, purchase amount, season, size, color
* **Shopping Behavior:** Discount applied, previous purchases, purchase frequency, review rating, shipping type

## 🛠️ Tools & Technologies

| Tool             | Purpose                                  |
| ---------------- | ---------------------------------------- |
| Python           | Data processing and analysis             |
| Pandas           | Data loading, cleaning, and manipulation |
| Jupyter Notebook | Python development and documentation     |
| PostgreSQL       | Database storage and SQL analysis        |
| SQL              | Business queries and customer analysis   |
| Power BI         | Interactive dashboard development        |
| Gamma            | Presentation and project PPT creation    |

## 🔄 Project Workflow

### 1. Data Loading

* Imported the dataset into Python using Pandas.
* Examined the dataset structure, data types, and summary statistics.

### 2. Exploratory Data Analysis (EDA)

* Analyzed customer demographics and purchasing patterns.
* Examined purchase amounts, product categories, and customer behavior.
* Identified missing values and potential data quality issues.

### 3. Data Cleaning & Feature Engineering

* Handled missing review ratings using the median rating of each product category.
* Standardized column names using snake_case.
* Created an `age_group` column to categorize customers by age.
* Created a `purchase_frequency_days` column.
* Checked for redundant columns and removed `promo_code_used`.
* Prepared the cleaned dataset for database analysis.

### 4. SQL Analysis

Connected Python to PostgreSQL and loaded the cleaned dataset into the database for structured analysis.

The project includes database connection code for PostgreSQL.

Key business questions explored:

1. Revenue comparison by gender.
2. High-spending customers who used discounts.
3. Top 5 products by average review rating.
4. Comparison of Standard and Express shipping purchase amounts.
5. Subscriber vs. non-subscriber spending and revenue.
6. Products with the highest percentage of discounted purchases.
7. Customer segmentation into New, Returning, and Loyal.
8. Top 3 most-purchased products in each category.
9. Relationship between repeat purchases and subscription status.
10. Revenue contribution by age group.

### 5. Power BI Dashboard

* Built an interactive dashboard to visualize customer shopping behavior.
* Presented key findings related to customer spending, product preferences, and subscription patterns.
* Organized insights to support business decision-making.

### 6. Business Report & Presentation

* Created a project report documenting the analysis and findings.
* Prepared a presentation using Gamma to communicate the project workflow, key insights, and business recommendations.

## 📊 Dashboard

The Power BI dashboard provides a visual overview of customer shopping patterns, revenue trends, and customer segments.

**Dashboard Preview:**

<img width="1227" height="669" alt="image" src="https://github.com/user-attachments/assets/b168d423-a27f-4a36-b38c-527f08027687" />


![Power BI Dashboard](images/dashboard.png)

**Power BI Dashboard:** [Add your dashboard link here]

## 📈 Results & Business Recommendations

The analysis supports the following business recommendations:

* **Increase Subscriptions:** Promote exclusive benefits to encourage more customers to subscribe.
* **Improve Customer Loyalty:** Introduce loyalty programs and rewards for repeat buyers.
* **Optimize Discount Strategy:** Review discount policies to balance sales growth with profit margins.
* **Improve Product Positioning:** Highlight highly rated and frequently purchased products in marketing campaigns.
* **Targeted Marketing:** Focus campaigns on high-revenue age groups and customers who prefer Express shipping.

## 📁 Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── notebooks/
│   └── Customer_Shopping_Behavior_Analysis.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── dashboard/
│   └── customer_shopping_behavior.pbix
│
├── presentation/
│   └── Customer_Shopping_Behavior_Presentation.pptx
│
├── images/
│   └── dashboard.png
│
└── README.md
```

## 🚀 How to Run

### Prerequisites

Install the following tools:

* Python 3.x
* Jupyter Notebook
* PostgreSQL
* Power BI Desktop


### Step 1: Install Python Libraries

```bash
pip install pandas sqlalchemy psycopg2-binary
```

### Step 2: Load the Dataset

Place the CSV file in the `data/` folder and load it into Python:

```python
import pandas as pd

df = pd.read_csv("data/customer_shopping_behavior.csv")

print(df.head())
print(df.info())
```

### Step 3: Run the Analysis

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Run the notebook cells in order to perform EDA, clean the dataset, create features, and load the data into your database.

### Step 4: Run SQL Queries

* Create a database in your preferred database system.
* Configure the database connection in Python.
* Load the cleaned dataset into the database.
* Execute the SQL queries to answer the business questions.

### Step 5: Open the Dashboard

Open the Power BI `.pbix` file in Power BI Desktop and configure the data connection if required.

## 🎯 Skills Demonstrated

* Data Cleaning and Preprocessing
* Exploratory Data Analysis (EDA)
* Python and Pandas
* SQL Query Writing and Business Analysis
* Database Connectivity and Integration
* Data Visualization using Power BI
* Customer Segmentation
* Business Reporting and Presentation
* Data-Driven Decision Making

## 👤 Author

**Kishan Patel**

Aspiring Data Analyst | Python | SQL | Power BI | Excel

* **GitHub:** [Add your GitHub profile link]
* **LinkedIn:** [Add your LinkedIn profile link]

---

*This project was developed as part of my data analytics portfolio to demonstrate an end-to-end approach to analyzing customer shopping behavior and generating actionable business insights.*
