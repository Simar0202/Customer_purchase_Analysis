# Customer_purchase_Analysis
Customer behavior analysis using Python, SQL, and Power BI with interactive dashboard and business insights.
# Customer Shopping Behavior Analysis Dashboard

## Overview

This project analyzes customer shopping behavior using Python, SQL, and Power BI. The objective was to clean and transform customer data, perform business-focused analysis, and develop an interactive dashboard to uncover insights related to customer demographics, purchasing patterns, product performance, and revenue trends.

The project demonstrates an end-to-end analytics workflow:

Data Cleaning → Data Transformation → SQL Analysis → Dashboard Development → Business Insights

---

## Tools & Technologies

### Python
- Pandas
- NumPy
- Google Colab

### SQL
- MySQL
- MySQL Workbench

### Data Visualization
- Power BI

### Other Tools
- GitHub
- CSV Data Handling

---

## Dataset Information

The dataset contains approximately 3,900 customer records and includes:

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
- Payment Method
- Frequency of Purchases

---

## Data Cleaning & Feature Engineering

### Age Segmentation

Created customer age groups using quartile-based segmentation:

- Young Adult
- Adult
- Middle-aged
- Senior

### Purchase Frequency Conversion

Converted purchase frequency values into numerical day equivalents:

| Frequency | Days |
|------------|------|
| Weekly | 7 |
| Bi-Weekly | 14 |
| Monthly | 30 |
| Quarterly | 90 |
| Annually | 365 |

### Data Validation

Performed consistency checks between discount-related columns to ensure data quality and accuracy.

---

## SQL Analysis

Business questions solved using MySQL:

### Customer Analysis
- Customer Segmentation (New, Returning, Loyal)
- Customer Distribution by Gender
- Customer Distribution by Age Group

### Revenue Analysis
- Revenue by Category
- Revenue by Gender
- Revenue by Age Group
- Revenue by Subscription Status

### Product Analysis
- Top Revenue-Generating Products
- Top Categories by Revenue
- Product Performance Analysis

### SQL Concepts Used
- Common Table Expressions (CTEs)
- Window Functions
- ROW_NUMBER()
- CASE Statements
- Aggregations
- GROUP BY
- Subqueries
- Ranking Functions

---

## Power BI Dashboard

### KPIs

- Total Customers
- Average Review Rating
- Average Purchase Amount
- Total Revenue

### Interactive Visualizations

- Revenue by Category
- Revenue by Gender
- Revenue by Age Group
- Customer Count by Category
- Customer Count by Age Group
- Top 2 Categories by Revenue
- Top 5 Products by Revenue
- Subscription Status Distribution

### Interactive Filters

- Subscription Status
- Gender
- Category
- Shipping Type

---

## Key Insights

### Category Performance
- Clothing generated the highest overall revenue.
- Accessories ranked as the second highest revenue-generating category.

### Product Performance
- Blouse, Shirt, Dress, Pants, and Jewelry were among the top revenue-generating products.

### Customer Demographics
- Young Adult customers contributed the highest share of revenue.
- Male customers generated higher revenue compared to female customers.

### Subscription Analysis
- A significant proportion of customers were active subscribers, indicating strong customer engagement.

---


## Project Structure


Customer-Shopping-Behavior-Analysis/
│
├── Customer_Behavior_Analysis.ipynb
├── customer_behavior.sql
├── Customer_Shopping_Behavior_Dashboard.pbix
├── cleaned_customer_data.csv
├── dashboard.png
└── README.md

---

## Skills Demonstrated

### Python
- Data Cleaning
- Data Transformation
- Exploratory Data Analysis

### SQL
- Query Writing
- Aggregations
- CTEs
- Window Functions
- Customer Segmentation

### Power BI
- Dashboard Development
- KPI Design
- Interactive Slicers
- Top N Filtering
- Data Storytelling


---

## Author

**Simarpreet Kaur**

**Data Analyst | Python | SQL | Power BI | Excel**

Passionate about transforming raw data into meaningful insights through analytics, visualization, and business intelligence solutions.
