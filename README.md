# Customer Behavior Analysis Dashboard

## Overview

This project analyzes customer shopping behavior to identify purchasing patterns, product performance, customer preferences, and subscription trends.

The project follows an end-to-end data analytics workflow, starting with data cleaning and preprocessing using Python and Pandas, followed by data storage and analysis using PostgreSQL and SQL, and finally presenting the insights through an interactive Power BI dashboard.

The main objective was to transform raw customer shopping data into meaningful business insights that can support data-driven decision-making.

## Objectives

- Analyze customer purchasing behavior
- Identify top-performing product categories
- Evaluate subscription trends among customers
- Track revenue and sales performance
- Build an interactive dashboard for business decision-making


## Tools & Technologies

- **Python** – Data cleaning and preprocessing
- **Pandas** – Data manipulation and transformation
- **Google Colab** – Python development environment
- **PostgreSQL** – Database storage and SQL analysis
- **pgAdmin 4** – GUI-based PostgreSQL management and query execution
- **SQL** – Data analysis and business insights
- **Power BI** – Interactive data visualization and dashboard creation
- **CSV** – Dataset storage and exchange

## Data Cleaning & Preprocessing

The raw customer shopping dataset was cleaned and prepared using Python and Pandas in Google Colab.

Key preprocessing steps included:

- Handling missing values
- Filling missing `Review Rating` values using the median rating within each product category
- Standardizing column names using `snake_case`
- Checking data types and data consistency
- Preparing the cleaned dataset for PostgreSQL analysis
- Exporting the cleaned dataset for database analysis

## Dashboard Features

### KPI Cards
- Total Customers
- Average Purchase Amount
- Average Review Rating

### Visualizations
- Revenue by Category
- Sales by Category
- Subscription Status Analysis
- Revenue by Age Group
- Sales by Age Group

### Interactive Filters
- Subscription Status
- Gender
- Category
- Shipping Type

## Dashboard Preview

![Dashboard](Image%20of%20Dashboard)

## Key Business Insights

- Clothing category generated the highest revenue among all categories.
- Majority of customers do not have an active subscription.
- Young Adult customers contributed the highest sales volume.
- Accessories emerged as the second-highest revenue-generating category.
- Customer purchasing behavior varies across different age groups.

## Dataset Information

The dataset contains customer shopping information including:

- Customer ID
- Age
- Gender
- Item Purchased
- Category
- Purchase Amount
- Location
- Size
- Color
- Season
- Review Rating
- Subscription Status
- Shipping Type
- Discount Applied
- Previous Purchases
- Frequency of Purchases

## Repository Contents

| File | Description |
|---|---|
| `customer_behavior_cleaned.csv` | Cleaned dataset used for analysis |
| `Customer behavior dashboard project.pbix` | Power BI dashboard |
| `SQL QUERIES FOR CUSTOMER DATA ANALYSIS.sql` | SQL queries used for analysis |
| `dashboard.png` | Dashboard preview |
| `README.md` | Project documentation |

## SQL Analysis

After preprocessing, the cleaned dataset was imported into PostgreSQL using pgAdmin 4.

SQL was used to perform business-oriented analysis and extract insights from the customer data.

### Key Analysis Performed

- Revenue analysis by gender
- Revenue analysis by product category
- Average customer spending
- Product-wise average review ratings
- Discount-based purchasing analysis
- Subscription status analysis
- Customer segmentation
- Purchasing frequency analysis
- Previous purchase analysis
- Identification of top-performing products
- Analysis of customers spending above the overall average

### SQL Concepts Used

- `SELECT`
- `WHERE`
- `GROUP BY`
- `ORDER BY`
- Aggregate functions such as `COUNT()`, `SUM()`, and `AVG()`
- `ROUND()`
- Subqueries
- Conditional filtering
- `CASE` statements

- ## Dashboard Preview

![Dashboard](Screenshot%202026-06-23%20204344.png)

## Future Improvements

- Customer Lifetime Value (CLV) analysis
- Customer churn prediction
- Sales forecasting
- More advanced customer segmentation
- Automation of the data processing pipeline

## Author

**Riya Goel**

B.Tech CSE Student | Data Analytics Enthusiast

GitHub: https://github.com/riyagoel0424



