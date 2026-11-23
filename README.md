# Olist E-Commerce Data Analysis

A beginner-to-intermediate data analytics project using the **Olist Brazilian E-Commerce Dataset (2016–2018)** to explore customer behavior, payments, product categories, and reviews.

## Tools
- **SQL (SQLite):** JOIN, GROUP BY, HAVING, CASE WHEN, CTE
- **Python:** Pandas, Matplotlib, Seaborn
- **Google Colab / Jupyter Notebook**

## What's Included
- Data quality checks for missing values and duplicates
- SQL analysis of orders, customers, payment methods, product categories, and reviews
- Visualizations of monthly payment trends and top product categories

## Key Findings
- Around **97%** of orders were marked as delivered.
- **São Paulo (SP)** had the largest number of unique customers.
- **Credit card** was the leading payment method by total payment value.
- Monthly payment value for delivered orders peaked in **November 2017**.

## How to Run
1. Download the nine CSV files from the [Olist dataset on Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce).
2. Put the CSV files in your Google Drive folder: `MyDrive/SQL Project`.
3. Open `olist_customers_fixed.ipynb` in Google Colab, mount Google Drive if needed, and select **Runtime → Run all**.

**Note:** This is a portfolio project using historical data. Missing values and duplicates are documented rather than removed blindly; category-level analysis excludes products without a mapped category.
