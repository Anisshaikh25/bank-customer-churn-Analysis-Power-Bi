# 📊 Bank Customer Churn Analysis Dashboard

## 🔍 Project Overview

Customer churn is one of the most important metrics for banks and financial institutions because **losing existing customers directly impacts revenue and growth**. Retaining customers is often significantly more cost-effective than acquiring new ones.

This project focuses on **analyzing customer behavior using Power BI** to identify patterns that lead to churn. By exploring customer demographics, financial attributes, and engagement metrics, the dashboard highlights key factors that influence whether a customer stays with the bank or decides to leave.

The interactive dashboard allows users to **explore churn patterns dynamically through filters and visualizations**, enabling better decision-making and customer retention strategies.

---

## 🎯 Project Objectives

* Analyze customer data to **identify patterns and trends in churn behavior**.
* Calculate the **overall churn rate and retention rate** of the bank.
* Understand how **demographics, financial status, and engagement** impact churn.
* Identify **high-risk customer segments**.
* Provide **data-driven insights** that can help banks improve customer retention.

---

## 🛠️ Tools & Technologies

| Tool                    | Purpose                                   |
| ----------------------- | ----------------------------------------- |
| **Power BI**            | Dashboard creation and data visualization |
| **Power Query**         | Data cleaning and transformation          |
| **DAX**                 | Creating KPIs and analytical measures     |
| **Excel / CSV Dataset** | Source data for analysis                  |

---

## 🧹 Data Cleaning & Preparation

Before building the dashboard, several preprocessing steps were performed:

* Removed unnecessary columns such as **RowNumber, CustomerId, and Surname**.
* Checked for **missing values and inconsistencies**.
* Created **customer segmentation groups** (e.g., Age Groups).
* Standardized categorical fields for easier analysis.
* Validated churn indicator values to ensure accurate KPI calculations.

---

## 📈 Key Performance Indicators (KPIs)

The dashboard tracks several important business metrics:

* **Total Customers** – Total number of customers in the dataset
* **Churned Customers** – Number of customers who left the bank
* **Churn Rate (%)** – Percentage of customers who exited
* **Retention Rate (%)** – Percentage of customers retained
* **Active Customer Percentage** – Customers actively using bank services
* **Average Account Balance** – Average balance maintained by customers

These KPIs help **quickly assess the bank's customer stability and retention performance**.

---

## 📊 Dashboard Features

The Power BI dashboard includes interactive visualizations to analyze churn patterns.

### Customer Overview

* Total customer base
* Churned vs retained customers
* Active vs inactive customers

### Demographic Analysis

* Churn distribution by **Gender**
* Churn comparison by **Age Group**
* Regional churn patterns by **Geography**

### Financial Insights

* Average balance comparison
* Product usage vs churn probability
* Salary distribution analysis

### Engagement & Behavior

* Churn based on **active membership**
* Impact of **customer complaints**
* Customer satisfaction trends

---

## 💡 Key Insights

Some notable insights identified from the analysis include:

* **Inactive customers are significantly more likely to churn.**
* Customers who **raise complaints tend to have a higher probability of leaving the bank**.
* Customers using **multiple banking products show stronger loyalty**.
* Certain **geographical regions experience higher churn rates** compared to others.

These insights can help financial institutions **identify risk segments and develop targeted retention strategies**.

---

## 📁 Project Structure

```
Bank-Churn-Analysis
│
├── bankChurnDash.pbix
├── Customer-Churn-Records.csv
└── README.md
```

---

## 🚀 How to Use the Dashboard

1. Download the `.pbix` file from this repository.
2. Open it using **Microsoft Power BI Desktop**.
3. Interact with the dashboard using **filters and slicers**.
4. Explore churn insights across different customer segments.

---

## 🔮 Future Improvements

* Implement a **machine learning churn prediction model**.
* Integrate the dashboard with **live or streaming banking data**.
* Add **customer lifetime value (CLV) analysis**.
* Include **advanced segmentation for churn risk detection**.

---

## 👨‍💻 Author

**Anis Shaikh**
Aspiring **Data Analyst** passionate about transforming raw data into actionable insights.

This project is part of my **data analytics portfolio**, demonstrating the ability to perform **data analysis, KPI development, and business intelligence reporting**.
