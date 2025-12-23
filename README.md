# 🛒 Retail Customer Shopping Behavior Analysis

## 📌 Project Overview

This project analyzes retail customer shopping behavior using historical transaction data to uncover purchasing patterns, customer segments, and key factors influencing spending and repeat purchases. The goal is to generate actionable insights that support **marketing optimization, customer retention, and data-driven business decisions**.

The analysis combines **Python for data preparation and EDA**, **SQL for structured analysis**, and **Power BI for visualization**.

---

## 🎯 Business Objective

* Identify purchasing trends and customer behavior patterns
* Segment customers based on purchase history and engagement
* Evaluate the impact of discounts, subscriptions, and shipping choices
* Provide insights to improve marketing effectiveness and retention strategies

---

## 📂 Dataset Summary

* **Total Records:** 3,900 transactions
* **Key Features:**

  * Customer demographics: Age, Gender, Location
  * Purchase details: Item, Category, Amount, Season, Size, Color
  * Behavioral data: Discounts, Subscription Status, Previous Purchases, Frequency
  * Feedback: Review Ratings
* **Missing Data:** 37 missing values in the `Review Rating` column

---

## 🧰 Tools & Technologies

* **Python:** pandas, numpy, matplotlib, seaborn
* **SQL:** PostgreSQL
* **Visualization:** Power BI
* **Environment:** Jupyter Notebook

---

## 🔍 Data Preparation & Analysis (Python)

* Loaded and explored the dataset using `pandas`
* Handled missing values by imputing median ratings per product category
* Standardized column names (snake_case)
* Performed feature engineering:

  * Created age groups
  * Derived purchase frequency in days
* Checked data consistency and removed redundant columns
* Exported cleaned data to PostgreSQL for SQL analysis

---

## 📊 Key Analyses Performed

* Revenue comparison by gender
* Spending behavior of discount users
* Top-rated products by average review score
* Purchase amount comparison by shipping type
* Subscriber vs non-subscriber revenue analysis
* Identification of discount-dependent products
* Customer segmentation (New, Returning, Loyal)
* Top products per category
* Subscription likelihood of repeat buyers
* Revenue contribution by age group

---

## 📈 Dashboard (Power BI)

An interactive Power BI dashboard was created to visualize:

* Customer segments
* Revenue trends
* Subscription impact
* Product and category performance

This dashboard is designed for **business stakeholders** to quickly interpret insights and make decisions.

---

## 💡 Business Recommendations

* **Boost Subscriptions:** Offer exclusive benefits to increase subscriber base
* **Loyalty Programs:** Incentivize repeat purchases to convert customers into loyal users
* **Optimize Discounts:** Balance sales growth with profitability
* **Product Positioning:** Promote top-rated and best-selling products
* **Targeted Marketing:** Focus on high-revenue age groups and express shipping users
---

## ✅ Key Takeaway

This project demonstrates an **end-to-end data analysis workflow**, from raw data cleaning to business insights and visualization, showcasing practical skills in **Python, SQL, and BI tools** for real-world retail analytics.

