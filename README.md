
# Customer Behavior Analytics Project

A complete end-to-end Data Analytics project focused on analyzing customer shopping behavior using **Python**, **SQL**, and **Power BI** to identify customer trends, improve engagement, and support business decision-making. The project includes data cleaning, business analysis, and dashboard visualization based on retail consumer data. 

---
<img width="1193" height="671" alt="Screenshot 2026-05-24 131222" src="https://github.com/user-attachments/assets/8d25ffaa-0a87-4fb5-aaf7-78ea2256ab8b" />

# Project Objective

The objective of this project is to analyze customer purchasing behavior across demographics, product categories, sales channels, and customer engagement metrics to generate actionable business insights. The analysis helps identify customer trends, optimize marketing strategies, and improve customer satisfaction. 

---

# Problem Statement

A leading retail company wants to better understand customer shopping behavior to improve sales, customer satisfaction, and long-term loyalty. The company is interested in analyzing factors such as:

* Demographics
* Product categories
* Discounts
* Subscription behavior
* Payment methods
* Seasonal purchasing patterns
* Online vs offline behavior

The main business question addressed in this project is:

> “How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?”

---

# Tools & Technologies Used

| Tool             | Purpose                       |
| ---------------- | ----------------------------- |
| Python           | Data Cleaning & Preprocessing |
| Pandas & NumPy   | Data Manipulation             |
| SQL              | Business Query Analysis       |
| Power BI         | Dashboard Visualization       |
| Jupyter Notebook | Development Environment       |



---

# Dataset Information

The dataset contains customer transaction records including:

* Customer demographics
* Product category
* Purchase amount
* Review rating
* Payment method
* Subscription status
* Shipping type
* Discounts applied
* Purchase frequency



---

# Project Workflow

```text
Data Collection
       ↓
Python Data Cleaning
       ↓
SQL Business Analysis
       ↓
Power BI Dashboard
       ↓
Insights & Recommendations
```

---

# Data Cleaning & Preprocessing (Python)

The dataset was cleaned and transformed using Python and Pandas. Major preprocessing steps included:

* Handling missing values
* Standardizing column names
* Removing redundant columns
* Creating customer age groups
* Converting purchase frequency into numerical values
* Data validation and transformation

Key preprocessing tasks performed:

```python
df.isnull().sum()
df.columns
pd.qcut()
```

Additional transformations included:

* Replacing missing review ratings with median values
* Converting categorical purchase frequencies into numerical day-based values
* Removing redundant columns such as `promo_code_used`



---

# SQL Business Analysis

SQL was used to answer important business questions related to customer behavior and purchasing patterns.

## Business Questions Answered

* Which customers spent above average despite discounts?
* Which products have the highest average review ratings?
* Do subscribed customers spend more?
* Which products receive the most discounts?
* What are the top-performing product categories?
* Which age groups contribute the highest revenue?
* Are repeat buyers more likely to subscribe?



---

# Power BI Dashboard

An interactive Power BI dashboard was developed to visualize customer purchasing trends and business performance.

## Dashboard Features

* KPI Cards
* Interactive Filters & Slicers
* Revenue Analysis
* Category-wise Sales
* Subscription Analysis
* Age Group Analysis

## KPIs Included

* Total Customers: 3.9K
* Average Purchase Amount: $59.76
* Average Review Rating: 3.75



---

# Key Insights

* Clothing category generated the highest revenue.
* Young Adults contributed the highest purchase amount.
* Most customers were non-subscribers.
* Customer behavior varied significantly across demographics.
* Discounts influenced purchasing behavior and repeat purchases.



---

# Recommendations

Based on the analysis, the following recommendations were provided:

* Focus marketing efforts on Young Adults.
* Improve low-performing categories using promotions.
* Increase subscription-based loyalty programs.
* Use customer reviews to improve product quality.
* Continuously monitor dashboard insights for strategic decisions.



---

# Conclusion

This project successfully demonstrates how Python, SQL, and Power BI can be integrated to perform complete business analysis and customer behavior analytics. The project provides meaningful insights into customer purchasing trends and supports data-driven decision-making for retail businesses. 

---

# Future Improvements

* Integrate real-time sales data
* Apply Machine Learning models for customer prediction
* Add advanced customer segmentation
* Automate ETL workflows
* Deploy dashboard to Power BI Service

---

# Project Structure

```text
Customer-Behavior-Analytics/
│
├── Dataset/
├── Python_Data_Cleaning/
├── SQL_Queries/
├── PowerBI_Dashboard/
├── Project_Report/
└── README.md
```

---




# Credits

-  Project Inspiration & Guidance: YouTube tutorial by Amlan Mohanty (@amlanmohanty1)
- Tools Used: Python, Pandas, SQL, Power BI

# Author

**Aravind G**
B.Com Graduate | MBA (HR)
Aspiring Data Analyst | Business Analytics Enthusiast

