# 💳 Credit Card Customer Churn Analysis

![Power BI](https://img.shields.io/badge/PowerBI-Dashboard-yellow?style=for-the-badge&logo=powerbi)
![Python](https://img.shields.io/badge/Python-EDA-blue?style=for-the-badge&logo=python)
![SQL](https://img.shields.io/badge/SQL-Analysis-orange?style=for-the-badge&logo=mysql)
![Excel](https://img.shields.io/badge/Excel-Data%20Analysis-green?style=for-the-badge&logo=microsoft-excel)
![License](https://img.shields.io/badge/Project-Type%20Data%20Analytics-blueviolet?style=for-the-badge)

---

⭐ If you like this project, consider giving it a **star** on GitHub!

---

# 📌 Project Overview

Customer churn is a major concern for financial institutions because retaining existing customers is significantly more cost-effective than acquiring new ones.

Understanding the behavioral and demographic factors that contribute to churn enables banks to develop targeted retention strategies.

This project analyzes customer churn behavior in a credit card dataset containing over **10,000 customers**.

The analysis combines **Excel, Python, SQL, and Power BI** to perform an **end-to-end data analytics workflow** and build an interactive dashboard providing actionable business insights.

---

# 📑 Table of Contents

- Project Overview
- Business Problem
- Dataset Information
- Project Workflow
- Tools & Technologies
- Exploratory Data Analysis
- SQL Analysis
- Power BI Dashboard
- Key Insights
- Business Recommendations
- Project Structure
- Dashboard Preview
- Skills Demonstrated
- Conclusion
- Author

---

# 🎯 Business Problem

Banks constantly face the challenge of **customer attrition**.

Losing customers directly impacts:

- Revenue
- Customer lifetime value
- Market competitiveness

This project answers key business questions:

- 📉 What percentage of customers are leaving the bank?
- 👥 Which customer segments show the highest churn risk?
- 💳 Does card category influence churn?
- ⏳ Do inactive customers churn more?
- 💰 Does transaction behavior impact churn?
- 📆 Do long-tenure customers show stronger loyalty?

These insights support **data-driven retention strategies**.

---

# 📊 Dataset Information

Dataset: **BankChurners**

Total Customers: **10,127**

Key dataset attributes:

| Category | Variables |
|--------|--------|
| Customer Demographics | Age, Gender, Income Category, Education |
| Account Information | Card Category, Credit Limit |
| Customer Engagement | Months on Book, Relationship Count |
| Activity Metrics | Transaction Amount, Transaction Count |
| Credit Behavior | Credit Utilization Ratio |
| Churn Indicator | Attrition Flag |

The dataset combines **behavioral, demographic, and financial attributes**, making it ideal for churn analysis.

---

# 🔄 Project Workflow

This project follows a **complete analytics pipeline**:

Dataset → Excel Analysis → Python EDA → SQL Analysis → Power BI Dashboard

Each stage contributed to discovering patterns and generating insights.

---

# 🛠 Tools & Technologies

| Tool | Purpose |
|------|------|
| 📊 Excel | Initial data exploration |
| 🐍 Python | Exploratory Data Analysis |
| 🗄 SQL | Business data queries |
| 📈 Power BI | Interactive dashboard |
| 📝 Markdown | Documentation |

---

# 🔎 Exploratory Data Analysis (Python)

Python was used for **exploratory data analysis** to identify patterns in the dataset.

Key analyses performed:

- Customer age distribution
- Credit utilization patterns
- Transaction behavior
- Relationship count distribution
- Churn distribution across segments

Libraries used:

Pandas  
Matplotlib  
Seaborn  
NumPy

These analyses helped identify **important churn indicators**.

---

# 🗄 SQL Analysis

SQL was used to perform **business-focused data queries**.

Examples of insights derived:

- Total customers vs churned customers
- Card category distribution
- Average credit limits across segments
- Transaction behavior comparison
- Customer tenure patterns

Example SQL query:

SELECT Attrition_Flag, COUNT(*) AS customer_count  
FROM bank_churn  
GROUP BY Attrition_Flag;

SQL enabled **structured exploration of churn patterns**.

---

# 📈 Power BI Dashboard

An **interactive Power BI dashboard** was developed to visualize insights.

The dashboard contains **two analytical pages**.

---

# 📊 Dashboard Page 1 — Executive Overview

This page provides a **high-level churn summary**.

Key KPIs:

- Total Customers
- Churned Customers
- Customer Churn Rate
- Average Credit Limit
- Average Customer Tenure

Key analyses:

- Overall churn distribution
- Churn by card category
- Churn by income segment
- Churn across age groups
- Customer inactivity vs churn

This page helps executives understand **where churn occurs**.

---

# 📊 Dashboard Page 2 — Customer Behavior Analysis

This page analyzes **behavioral drivers of churn**.

Behavioral KPIs:

- Average Transaction Amount
- Average Transaction Count
- Average Credit Utilization Ratio

Key behavioral insights:

- Credit utilization distribution
- Transaction activity vs churn
- Relationship count vs churn
- Customer tenure vs churn

This page identifies **customer engagement patterns**.

---

# 🔑 Key Insights

Important findings from the analysis:

- Customer churn rate ≈ **16%**
- Most customers use **less than 30% of their credit limit**
- Low transaction activity strongly correlates with churn
- Customers with multiple banking products show **higher retention**
- Long-tenure customers demonstrate **stronger loyalty**
- Card category influences churn patterns

---

# 💡 Business Recommendations

### Improve Customer Engagement
Encourage transaction activity through targeted offers.

### Cross-Sell Banking Products
Customers with multiple products show lower churn risk.

### Monitor Inactive Customers
Early detection of inactivity helps prevent churn.

### Reward Loyal Customers
Introduce loyalty programs for long-tenure customers.

---

# 📁 Project Structure

Credit-Card-Churn-Analysis

Dataset  
 └ BankChurners.csv  

Excel  
 └ Excel_Analysis.xlsx  

Python-EDA  
 └ churn_analysis.ipynb  

SQL  
 ├ 01_database_setup.sql  
 ├ 02_table_creation.sql  
 ├ 03_data_verification.sql  
 ├ 04_business_queries.sql  
 └ SQL_Query_Documentation.md  

PowerBI  
 └ Credit-Card-Churn-Analysis-Dashboard.pbix  

Screenshots  
 ├ Customer-Churn-Dashboard-Executive-Overview.png  
 └ Customer-Churn-Dashboard-Behavior-Analysis.png  

README.md

---

# 🖥 Dashboard Preview

### Executive Overview

![Dashboard Page 1](Screenshots/Customer-Churn-Dashboard-Executive-Overview.png)

### Customer Behavior Analysis

![Dashboard Page 2](Screenshots/Customer-Churn-Dashboard-Behavior-Analysis.png)

---

# 🚀 Skills Demonstrated

- Data Cleaning & Preparation
- Exploratory Data Analysis
- SQL Data Querying
- Business Intelligence Dashboard Design
- Data Visualization
- Data Storytelling
- Customer Behavior Analytics

---

# 📌 Conclusion

This project demonstrates how **data analytics can uncover customer churn patterns** in the financial services industry.

By combining demographic, behavioral, and financial data, this analysis highlights factors influencing customer retention and provides actionable insights for improving engagement strategies.

---

# 👨‍💻 Author

**Aatreya Pal**

B.Com Graduate | Aspiring Data Analyst

Skills:  
SQL | Python | Power BI | Excel | Data Visualization | Business Analytics

LinkedIn:  https://www.linkedin.com/in/aatreya-pal-403ba8237


