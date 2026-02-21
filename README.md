<p align="center">
   <a href="https://github.com/alitekn07/Python-Ecommerce-Business-Analysis">
  <img src="https://i.imgur.com/rd5zyuG.jpeg" alt="Project Cover Image"/>
     </a>
</p>

# 📊 Python E-Commerce Data Analysis – Sales, Product & Customer Insights

## 📌 Project Overview

This project is a comprehensive **end-to-end Python data analysis portfolio project** built using a real-world e-commerce dataset.

The objective is to analyze:

- Business performance  
- Customer behavior  
- Product performance  
- Revenue concentration  
- Price distribution  
- RFM-based customer segmentation  

The project simulates a real-world **Data Analyst workflow**, including data cleaning, transformation, feature engineering, exploratory analysis, visualization, and business insight generation.

**Dataset period:**  
September 2016 – October 2018

## 🎯 Business Objectives

- Evaluate overall revenue performance  
- Analyze order volume trends  
- Identify top-performing product categories  
- Measure revenue concentration (Pareto Analysis)  
- Examine customer behavior patterns  
- Segment customers using RFM methodology  
- Detect high-value, loyal, and at-risk customers  

## Dataset Description

**Source:** Brazilian E-Commerce Public Dataset by Olist (Kaggle)

Main datasets used:

- `olist_orders_dataset.csv`
- `olist_order_items_dataset.csv`
- `olist_products_dataset.csv`
- `olist_customers_dataset.csv`
- `product_category_name_translation.csv`

Only **delivered orders** were included to reflect completed transactions.

Data preparation included:

- Merging relational tables  
- Handling date-time columns  
- Feature engineering (revenue calculation)  
- Cleaning missing values  
- Filtering relevant business metrics  

## Data Preparation & Engineering

The project follows a structured data preparation process:

- Table joins using Pandas  
- Revenue calculation per order item  
- Datetime conversion & Recency calculation  
- Customer-level aggregation  
- Category-level performance aggregation  
- Product-level revenue ranking  

Key engineered features:

- `revenue`
- `order_count`
- `avg_price`
- `recency`
- `frequency`
- `monetary`

## Analysis Structure

### 1. Business Overview
- Monthly Revenue Trend  
- Revenue Contribution by Category  
- Pareto Revenue Distribution  

### 2. Customer Analysis
- Customer Order Frequency Distribution  
- Revenue by Customer Type (One-Time vs Repeat)  
- Customer Revenue Pareto Curve  
- Average Order Value Comparison  

### 3. Product Analysis
- Top 10 Categories by Revenue  
- Revenue vs Order Volume Comparison  
- Revenue per Order by Category  
- Product-Level Revenue Concentration (Top 10 / Top 50)  
- Price Distribution Analysis  
- Average Price by Category  
- Price vs Revenue Relationship (Correlation & Scatter Analysis)  

### 4. RFM Segmentation
- Recency Calculation  
- Frequency Calculation  
- Monetary Value Calculation  
- RFM Scoring  
- Customer Segment Classification  
- Identification of:
  - Champions  
  - Loyal Customers  
  - Potential Loyalists  
  - At Risk  
  - Lost Customers  

## 📂 Project Structure


```
python-ecommerce-analysis/
    ├── data/raw/
    │   ├── olist_orders_dataset.csv
    │   ├── olist_order_items_dataset.csv
    │   ├── olist_products_dataset.csv
    │   ├── olist_customers_dataset.csv
    │   └── product_category_name_translation.csv
    │
    ├── notebooks/
    │   ├── 01_business_overview.ipynb
    │   ├── 02_customer_analysis.ipynb
    │   ├── 03_product_analysis.ipynb
    │   └── 04_rfm_segmentation.ipynb
    │
    ├── outputs/
    │   ├── 01_*.png
    │   ├── 02_*.png
    │   ├── 03_*.png
    │   └── 04_*.png
    │
    ├── reports/
    │   └── business_summary.pdf
    │
    └── README.md

```
## 📊 Outputs

The project provides:

- Executive-level business insights  
- Customer behavior analysis  
- Revenue concentration findings  
- Product-level performance breakdown  
- RFM-based segmentation strategy  

All visualizations were created using Matplotlib and Seaborn.

## 🛠 Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Exploratory Data Analysis (EDA)  
- RFM Modeling  

## 🧠 Key Insights

- Revenue shows consistent growth across the analyzed period.  
- A small number of categories contribute disproportionately to total revenue (Pareto effect).  
- Revenue concentration at the product level is relatively distributed (low top 10 dominance).  
- The majority of customers are one-time buyers, indicating retention opportunity.  
- High-value customers can be clearly identified using RFM scoring.  
- Average price and total revenue show weak correlation at category level, indicating volume-driven revenue in many segments.  

## 🎤 Summary

This project demonstrates a complete analytical workflow using Python, from raw data processing to business-level insight generation.

It highlights practical data analysis skills including:

- Data wrangling  
- Aggregation & feature engineering  
- Visualization  
- Revenue analysis  
- Customer segmentation  

The project simulates a real-world Data Analyst scenario and focuses on translating raw data into meaningful business decisions.

## 📄 Disclaimer

This project was created for educational and portfolio purposes.

All data modeling, analytical logic, visualizations, and RFM segmentation methodology were independently developed by the author.

The dataset used in this project is publicly available on Kaggle.  
No proprietary or confidential data was used.

All rights to the analytical structure and presentation belong to the author.  
Unauthorized copying or redistribution without attribution is discouraged.

                                                               © 2026 Ali Tekin. All rights reserved.























