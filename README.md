# customer_behviour_project
# Customer Behavior Analysis using Python, SQL & Power BI

## Project Overview
This project focuses on analyzing customer purchasing behavior using Python for data cleaning and preprocessing, SQL for business analysis, and Power BI for interactive dashboard visualization. The objective of the project was to identify customer trends, purchasing patterns, subscription behavior, and category-wise sales performance.

<img width="1193" height="671" alt="Screenshot 2026-05-24 131222" src="https://github.com/user-attachments/assets/8d25ffaa-0a87-4fb5-aaf7-78ea2256ab8b" />

---

# Objectives
- Clean and preprocess raw customer data.
- Perform business analysis using SQL queries.
- Analyze customer demographics and purchasing behavior.
- Create an interactive Power BI dashboard for visualization.
- Generate business insights and recommendations.

---

# Tools & Technologies Used

| Tool | Purpose |
|---|---|
| Python | Data Cleaning & Preprocessing |
| Pandas | Data Manipulation |
| SQL | Business Query Analysis |
| Power BI | Dashboard Visualization |

---

# Data Cleaning & Preprocessing (Python)

The following preprocessing steps were performed using Python and Pandas:

- Imported the dataset using Pandas.
- Checked dataset structure using `head()`.
- Used `describe()` for statistical analysis.
- Identified missing values using `isnull().sum()`.
- Filled missing values in `Review Rating` using median values.
- Standardized column names by:
  - converting to lowercase
  - replacing spaces with underscores
- Renamed columns for better readability.
- Created customer age groups using `pd.qcut()`.
- Converted purchase frequency values into numerical day-based values.
- Removed redundant columns after validation checks.

---

# SQL Analysis

SQL queries were used to answer business-related questions such as:

- Which category generated the highest revenue?
- Which age group contributed the most sales?
- Subscription status distribution
- Customer purchasing trends
- Revenue by category

---

# Power BI Dashboard

The dashboard includes:

## KPI Cards
- Total Customers
- Average Purchase Amount
- Average Review Rating

## Visualizations
- Subscription Status Distribution
- Purchase Amount by Category
- Revenue by Age Group
- Category-wise Sales Analysis

## Interactive Filters
- Gender
- Age Group
- Subscription Status

---

# Key Insights

- Clothing category generated the highest revenue.
- Young Adults contributed the highest purchase amount.
- Most customers were non-subscribers.
- Customer purchasing behavior varied across categories and demographics.

---

# Recommendations

- Focus marketing on high-performing categories.
- Improve low-performing category sales through promotions.
- Increase subscription conversion using loyalty benefits.
- Use customer insights for personalized marketing strategies.

---

# Conclusion

This project successfully demonstrated the complete data analytics workflow including data cleaning, preprocessing, SQL-based analysis, and dashboard visualization. The insights generated from the analysis can support better business decision-making and improve customer engagement strategies.

---

# Future Improvements

- Add predictive analytics using Machine Learning.
- Connect Power BI with live databases.
- Automate the ETL pipeline.
- Develop advanced customer segmentation models.

---

# Credits

-  Project Inspiration & Guidance: YouTube tutorial by Amlan Mohanty (@amlanmohanty1)
- Tools Used: Python, Pandas, SQL, Power BI

