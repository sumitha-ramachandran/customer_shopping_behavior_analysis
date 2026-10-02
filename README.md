# Customer Shopping Behavior Analysis

## 📊 Overview

This project analyzes customer shopping behavior to understand purchasing patterns, customer segments, product performance, subscription behavior, and revenue trends.

The analysis was carried out using Python for data exploration and preparation, PostgreSQL for SQL-based analysis, and Power BI for creating an interactive dashboard.

## 📁 Dataset

The dataset contains 3,900 customer records and 18 columns covering customer demographics, purchasing behavior, products, discounts, subscriptions, ratings, and shipping information.

Key attributes include:

- Customer demographics
- Item purchased
- Category
- Purchase amount
- Discount applied
- Previous purchases
- Subscription status
- Shipping type
- Review rating
- Age and age groups

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- PostgreSQL
- pgAdmin
- Power BI
- Gamma

## 🔍 Project Workflow

### 1. Data Loading & Exploration

The dataset was loaded into Python using Pandas.

Initial exploration was performed to understand:

- Dataset structure
- Data types
- Missing values
- Duplicate records
- Numerical and categorical columns
- Basic statistical information

### 2. Data Cleaning & Preparation

The data was cleaned and prepared for analysis by checking data quality and creating useful categories for analysis.

Age groups were created to compare customer behavior across different age segments.

### 3. SQL Analysis

The cleaned dataset was loaded into PostgreSQL for further analysis.

SQL queries were used to analyze:

- Discount rates by product
- Customer segmentation based on previous purchases
- Top products within each category
- Subscription status among repeat customers
- Revenue contribution by age group
- Customer and product-level purchasing patterns

Customer segments were classified based on previous purchases:

| Segment | Previous Purchases |
|---|---:|
| New | 1 |
| Returning | 2–10 |
| Loyal | >10 |

Window functions such as `ROW_NUMBER()` were used to identify the top products within each category.

## 📈 Power BI Dashboard

An interactive Power BI dashboard was created to present the main findings from the analysis.

The dashboard includes:

- Total number of customers
- Average purchase amount
- Average rating
- Subscription status by gender
- Revenue by category
- Sales by category
- Revenue by age group
- Sales by age group
- Interactive slicers for customer attributes

### Key Dashboard Metrics

- **3.9K** Customers
- **$59.76** Average Purchase Amount
- **3.75** Average Rating

## 📌 Key Results

The analysis provided insights into customer purchasing behavior, product performance, subscription patterns, and revenue distribution.

Some of the findings include:

- Hats had the highest discount rate among the analyzed products.
- Customers were segmented into New, Returning, and Loyal groups based on previous purchases.
- Top-performing products were identified within each category.
- Repeat customers were analyzed based on their subscription status.
- Revenue was compared across different age groups.

## 📂 Project Files

| File | Description |
|---|---|
| `customer_shopping_behavior.csv` | Dataset |
| `customer_shopping_behavior_queries.sql` | PostgreSQL queries |
| `customer_shopping_behavior_analysis.ipynb` | Python analysis |
| `customer_shopping_behavior_analysis.pdf` | Project report |
| `README.md` | Project documentation |

## ▶️ How to Run

- Open the Jupyter Notebook to view the Python analysis.
- Run the SQL queries in PostgreSQL/pgAdmin.
- Open the Power BI dashboard to explore the visualizations.

## 📑 Project Presentation

[View Project Presentation](https://gamma.app/docs/Customer-growth-is-a-loyalty-and-conversion-problem-2g61nrz2mhgoqh8)

## 👩‍💻 Author

**Sumitha Ramachandran**

Data Analytics | SQL | Power BI | Python
