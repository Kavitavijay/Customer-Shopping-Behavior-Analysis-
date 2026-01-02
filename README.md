# Customer-Shopping-Behavior-Analysis-
End-to-end data analytics project analyzing 3,900 retail transactions using Python, SQL, and Power BI. The project uncovers customer segments, spending patterns, subscription impact, and discount behavior to deliver actionable business insights and data-driven recommendations.

# 🛍️ Customer Shopping Behavior Analysis

## 📌 Project Overview
This project analyzes customer shopping behavior using retail transactional data to uncover insights that help improve **sales performance, customer engagement, and marketing strategies**.

The analysis explores how **demographics, discounts, subscriptions, shipping preferences, and product ratings** influence customer purchasing decisions.

📊 Dataset includes **3,900 purchase records** across multiple product categories.

---

## 🎯 Business Problem
A retail company observed changes in customer purchasing patterns across demographics, product categories, and sales channels.

**Business Question:**
> How can consumer shopping data be leveraged to identify trends, improve customer engagement, and optimize marketing and product strategies?

---

## 🗂️ Dataset Summary
- **Rows:** 3,900  
- **Columns:** 18  
- **Key Features:**
  - Customer demographics (Age, Gender, Location)
  - Purchase details (Item, Category, Amount, Season)
  - Shopping behavior (Discount Applied, Shipping Type, Review Rating)
  - Subscription and loyalty indicators
- **Missing Values:**  
  - 37 missing values in `review_rating`

---

## 🛠️ Tools & Technologies
- **Python** (Pandas, NumPy)
- **SQL** (MS SQL Server / PostgreSQL)
- **Power BI**
- **GitHub**

---

## 🔍 Data Preparation (Python)
- Imported dataset using Pandas
- Performed exploratory analysis (`info()`, `describe()`)
- Handled missing values using **median imputation by category**
- Standardized column names (snake_case)
- Feature engineering:
  - `age_group`
  - `purchase_frequency_days`
- Removed redundant column (`promo_code_used`)
- Loaded cleaned data into SQL database

---

## 📊 Data Analysis (SQL)
Key business insights were extracted using SQL queries:

1. Revenue by gender  
2. High-spending customers using discounts  
3. Top 5 products by average rating  
4. Shipping type vs average purchase amount  
5. Subscriber vs non-subscriber spending  
6. Discount-dependent products  
7. Customer segmentation (New, Returning, Loyal)  
8. Top 3 products per category  
9. Repeat purchases vs subscriptions  
10. Revenue by age group  

---

## 📈 Power BI Dashboard
An interactive Power BI dashboard was built to visualize:
- Revenue trends
- Customer segmentation
- Subscription impact
- Shipping preferences
- Top-rated and best-selling products

---

## 💡 Key Insights
- Female customers generate slightly higher total revenue
- Express shipping users spend ~12% more per order
- Subscribers spend **68% more** than non-subscribers
- Loyal customers provide the highest lifetime value
- Some products are highly discount-dependent

---

## 📢 Business Recommendations
- Promote subscription plans with exclusive benefits
- Introduce loyalty programs to increase retention
- Optimize discount strategies to protect profit margins
- Highlight top-rated products in marketing campaigns
- Target high-revenue age groups and express-shipping users

---

## 📁 Repository Structure
Customer-Shopping-Behavior-Analysis/
│
├── data/ # Raw and cleaned datasets
├── python/ # Data cleaning & preprocessing scripts
├── sql/ # SQL analysis queries
├── powerbi/ # Power BI dashboard
├── reports/ # Project report & presentation
└── README.md

---

## 🚀 Why This Project Matters
- Demonstrates end-to-end **data analytics workflow**
- Combines **Python, SQL, and BI tools**
- Business-focused insights & recommendations
- Suitable for **Data Analyst / Business Analyst fresher roles**

---

## 📬 Author
**Kavita**  
Aspiring Data Analyst | Open to Work  
GitHub • LinkedIn
