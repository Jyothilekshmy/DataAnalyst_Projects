# 🛒 Customer Shopping Behavior Analysis

## 📌 Project Overview

This project analyzes customer shopping behavior using transactional data from **3,900 purchases** across various product categories. The goal is to uncover insights into spending patterns, customer segments, subscription behavior, and product preferences to support data-driven business decisions.

The project follows an end-to-end analytics workflow using **Python**, **PostgreSQL**, and **Power BI**.

---

## 🎯 Objectives

- Analyze customer purchasing behavior
- Identify high-revenue customer segments
- Evaluate the impact of discounts on spending
- Study subscription trends and customer loyalty
- Discover top-performing products and categories
- Generate actionable business recommendations

---

## 🛠️ Tools & Technologies

- **Python**
  - Pandas
  - NumPy
- **PostgreSQL**
- **SQL**
- **Power BI**

---

## 📊 Dataset Information

- **Total Records:** 3,900
- **Features:** 18

### Key Attributes

#### Customer Information
- Age
- Gender
- Location
- Subscription Status

#### Purchase Details
- Item Purchased
- Category
- Purchase Amount
- Season
- Size
- Color

#### Shopping Behavior
- Discount Applied
- Previous Purchases
- Purchase Frequency
- Review Rating
- Shipping Type

---

## ⚙️ Project Workflow

### 1. Data Cleaning & Preprocessing
- Loaded dataset using Pandas
- Checked data quality and structure
- Handled missing values
- Standardized column names
- Removed redundant columns

### 2. Feature Engineering
- Created customer age groups
- Derived purchase frequency metrics
- Improved dataset usability for analysis

### 3. PostgreSQL Integration
- Connected Python to PostgreSQL
- Loaded cleaned dataset into the database
- Prepared data for SQL-based analysis

### 4. Business Analysis Using SQL
- Revenue by Gender
- High-Spending Discount Users
- Top-Rated Products
- Shipping Type Comparison
- Subscribers vs Non-Subscribers Analysis
- Discount-Dependent Products
- Customer Segmentation
- Top Products by Category
- Repeat Buyer Analysis
- Revenue by Age Group

### 5. Dashboard Development
Built an interactive Power BI dashboard to visualize:
- Revenue trends
- Customer demographics
- Subscription behavior
- Product performance
- Customer segmentation
- Shopping patterns

---

## 📈 Dashboard Highlights

- **Total Revenue:** $233K
- **Average Purchase Value:** $59.76
- **Average Customer Rating:** 3.75/5
- **Subscribers:** 27%
- **Non-Subscribers:** 73%
- **Top Product Category:** Clothing
- **Highest Revenue Age Group:** Young Adults

---

## 🔍 Key Business Questions

- Which customer segments generate the highest revenue?
- Do discounts encourage higher spending?
- Are repeat buyers more likely to subscribe?
- Which products depend heavily on discounts?
- How do age groups influence revenue?

---

## 💡 Key Insights

- Clothing emerged as the highest-performing category.
- Young Adults contributed the largest share of revenue.
- Subscription adoption remains relatively low, presenting growth opportunities.
- Loyal customers can be identified through purchase history patterns.
- Discount strategies significantly influence purchasing behavior.

---

## 🚀 Business Recommendations

- Strengthen customer loyalty programs
- Improve subscription adoption strategies
- Optimize discount policies
- Promote top-performing products
- Implement targeted marketing campaigns

---

## 📂 Project Structure

Customer-Shopping-Behavior-Analysis/
│
├── data/
│ ├── raw_data.csv
│ └── cleaned_data.csv
│
├── notebooks/
│ └── data_cleaning_analysis.ipynb
│
├── sql/
│ └── business_queries.sql
│
├── dashboard/
│ └── customer_shopping_dashboard.pbix
│
├── images/
│ └── dashboard_screenshot.png
│
└── README.md

---

## 📌 Conclusion

This project demonstrates a complete data analytics workflow—from data cleaning and transformation to SQL-based business analysis and dashboard development. The insights generated help businesses better understand customer behavior and make informed strategic decisions.
