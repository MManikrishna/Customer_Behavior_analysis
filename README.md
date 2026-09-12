# Customer Shopping Behavior Analysis

## 📌 Project Overview

Customer Shopping Behavior Analysis is an end-to-end data analytics project focused on understanding customer purchasing patterns, product preferences, subscription behavior, and revenue contribution across different customer segments.

The project analyzes **3,900 customer purchase records** using Python, PostgreSQL, SQL, and Power BI to transform raw transactional data into meaningful business insights.

The objective is to help a retail business understand customer behavior, identify high-value segments, evaluate promotional strategies, and support data-driven business decisions.

---

## 🎯 Business Problem

A leading retail company wants to better understand its customers' shopping behavior in order to improve sales, customer satisfaction, and long-term customer loyalty.

Management is particularly interested in understanding:

- Customer spending patterns
- Product and category performance
- Subscription behavior
- Impact of discounts and promotions
- Customer loyalty and repeat purchases
- Revenue contribution across age groups
- Shipping preferences
- Product ratings and customer satisfaction

The analysis aims to answer these business questions and provide actionable recommendations.

---

## 📊 Dataset

The dataset contains **3,900 purchase records** and **18 columns**.

### Key Features

#### Customer Information
- Age
- Gender
- Location
- Subscription Status

#### Purchase Information
- Item Purchased
- Category
- Purchase Amount
- Season
- Size
- Color

#### Shopping Behavior
- Discount Applied
- Promo Code Used
- Previous Purchases
- Frequency of Purchases
- Review Rating
- Shipping Type

### Missing Data

There were **37 missing values** in the `Review Rating` column.

These values were handled using the **median review rating within each product category**.

---

## 🛠️ Tools & Technologies

- **Python**
  - Pandas
  - NumPy
  - Data Cleaning
  - Exploratory Data Analysis
- **PostgreSQL**
- **SQL**
  - Aggregations
  - GROUP BY
  - CASE statements
  - Window Functions
  - Subqueries
  - CTEs
- **Power BI**
  - Interactive Dashboard
  - KPIs
  - Slicers
  - Charts & Visualizations
- **Jupyter Notebook**
- **Git & GitHub**

---

# 🔄 Project Workflow

```text
Raw Dataset
     ↓
Data Loading using Python
     ↓
Data Exploration
     ↓
Data Cleaning
     ↓
Feature Engineering
     ↓
PostgreSQL Database Integration
     ↓
SQL Business Analysis
     ↓
Power BI Dashboard
     ↓
Business Insights
     ↓
Business Recommendations
