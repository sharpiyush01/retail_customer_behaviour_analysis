# 🛒 Retail Customer Shopping Behavior Analysis

Analyzing customer purchasing behavior, segmentation, and retention drivers to support data-driven marketing and business decisions using **Python, SQL, and Power BI**.

---

## 📌 Table of Contents
- Overview  
- Business Problem  
- Dataset  
- Tools & Technologies  
- Project Structure  
- Data Cleaning & Preparation  
- Exploratory Data Analysis (EDA)  
- Research Questions & Key Findings  
- Dashboard  
- How to Run This Project  
- Final Recommendations  
- Author & Contact  

---

## Overview
This project analyzes retail customer shopping behavior using historical transaction data to uncover purchasing patterns, customer segments, and key factors influencing spending and repeat purchases.

A complete analytics workflow was implemented using **Python** for data cleaning and exploratory analysis, **SQL** for structured querying, and **Power BI** for visualization, with the goal of generating actionable insights for marketing optimization and customer retention.

---

## Business Problem
Retail businesses collect large volumes of customer transaction data but often lack clarity on how different customer segments behave and what drives repeat purchases. Changes in customer demographics, discount sensitivity, subscription usage, and shipping preferences make broad marketing strategies inefficient.

This project aims to:
- Understand customer purchasing behavior and engagement patterns  
- Identify high-value and repeat customer segments  
- Evaluate the effectiveness of discounts, subscriptions, and shipping options  
- Support targeted marketing and retention strategies  

---

## Dataset
**Total Records:** 3,900 retail transactions  

**Key Features:**
- Customer demographics (Age, Gender, Location)  
- Purchase details (Item, Category, Amount, Season, Size, Color)  
- Behavioral data (Discount Applied, Subscription Status, Previous Purchases, Purchase Frequency, Shipping Type)  
- Customer feedback (Review Rating)  

**Missing Data:**
- 37 missing values in the `review_rating` column  

---

## Tools & Technologies
- **Python** (pandas, numpy, matplotlib, seaborn)  
- **SQL** (PostgreSQL)  
- **Power BI** (Interactive Dashboards)  
- **Jupyter Notebook**  
- **GitHub**  

---

## Project Structure
```text
retail-customer-shopping-behavior/
│
├── README.md
├── .gitignore
├── retail_customer_shopping_behaviour.sql
├── retail_customer_report.pdf
├── retail_customer_presentation.pdf
│
├── notebooks/
│   └── retail_customer_shopping_behavior.ipynb
│
├── dashboard/
│   └── retail_customer_dashboard.pbix
│
├── images/
│   └── retail_customer_dashboard.jpg
````

---

## Data Cleaning & Preparation

* Loaded and inspected data using pandas
* Standardized column names to `snake_case`
* Handled missing `review_rating` values using **median imputation by product category**
* Performed feature engineering:

  * Created age groups for demographic analysis
  * Derived purchase frequency (in days) from historical purchases
* Checked data consistency and removed redundant columns
* Exported cleaned data to PostgreSQL for SQL analysis

---

## Exploratory Data Analysis (EDA)

### Customer Behavior Insights

* Balanced customer distribution across age groups
* Variation in spending based on gender and shipping type
* Discount usage does not always correlate with low spending

### Behavioral Patterns Observed

* Express shipping users show higher average purchase values
* Repeat buyers exhibit higher likelihood of subscription adoption
* Certain products are heavily dependent on discounts

---

## Research Questions & Key Findings

**Who drives the most revenue?**

* Male customers contributed higher total revenue overall

**Do discounts attract high-value customers?**

* Several discount users still spend above the average purchase amount

**Does shipping type impact spending?**

* Express shipping users spend more on average than standard shipping users

**Are subscriptions linked to loyalty?**

* Repeat buyers are significantly more likely to subscribe

**Which products are discount-dependent?**

* A subset of products shows a high percentage of discounted purchases

**Customer Segmentation**

* Customers classified into **New**, **Returning**, and **Loyal** segments based on purchase history

---

## Dashboard

The Power BI dashboard highlights:

* Customer segmentation
* Revenue trends by demographics
* Subscription impact on spending
* Product and category performance

The dashboard enables business users to filter insights by customer attributes and purchasing behavior.

---

## How to Run This Project

Clone the repository:

```bash
git clone https://github.com/sharpiyush01/retail-customer-behaviour-analysis-sql-python-powerBI.git
```

---

## Final Recommendations

* Increase subscription adoption through exclusive benefits for repeat buyers
* Implement loyalty programs to convert returning customers into loyal users
* Optimize discount strategies to protect margins while maintaining sales volume
* Promote high-rated and high-selling products
* Focus targeted marketing on high-revenue age groups and express shipping users

---

## Author & Contact

**Piyush Sharma**
*Data Analyst*

📧 Email: **[shar.piyush.01@gmail.com](mailto:shar.piyush.01@gmail.com)**
🔗 LinkedIn: [https://www.linkedin.com/in/sharpiyush01/](https://www.linkedin.com/in/sharpiyush01/)

