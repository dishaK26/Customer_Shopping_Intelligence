# 🛍️ Customer Shopping Behavior Analysis

An end-to-end **Data Analytics project** analyzing customer shopping behavior to identify purchasing patterns, customer segments, product-category performance, and subscription behavior.

Want to know about my project insights in brief, Refer this : "Documentation_Project_Shopping_Behavior.docx"
---
(file attached)
---

## 📌 Project Overview

The goal of this project was to transform raw customer shopping data into meaningful business insights using **Python, SQL, and Power BI**.

The analysis focuses on:

- Customer purchasing behavior
- Product category performance
- Customer demographics
- Subscription adoption
- Purchase frequency
- Review ratings
- Revenue and sales patterns

The project follows:

**Data Understanding → Data Cleaning → Data Preprocessing → EDA → SQL Analysis → Power BI Visualization → Business Insights**

---

##  Tech Stack

| Tool | Purpose |
|---|---|
| 🐍 Python | Data analysis and preprocessing |
| 🐼 Pandas | Data cleaning and manipulation |
| 📓 Jupyter Notebook | Exploratory analysis |
| 🗄️ SQL | Business-oriented data analysis |
| 🔗 SQLAlchemy | Python–SQL connection |
| 📊 Power BI | Interactive dashboard and visualization |

---

## 📂 Dataset

**Source:** Kaggle

The dataset contains customer shopping information including attributes related to:

- Customer demographics
- Gender
- Age/Age Group
- Product Category
- Purchase Amount
- Review Rating
- Subscription Status
- Purchase Frequency
- Previous Purchases
- Payment Method
- Items Purchased

**Dataset Size:** ~4,000 customer records

---

## 🔍 Analysis Performed

### 1. Data Cleaning

- Inspected dataset structure and data types
- Checked missing values
- Standardized column names
- Handled missing review ratings using median imputation
- Cleaned and transformed categorical variables
- Standardized purchase-frequency categories

### 2. Exploratory Data Analysis

Analyzed:

- Average purchase amount
- Average review rating
- Customer distribution
- Purchase frequency
- Category performance
- Customer demographics
- Subscription status
- Revenue and sales patterns

### 3. SQL Analysis

Used SQL to answer business questions such as:

- What is the average purchase amount by subscription status?
- Which categories generate the highest total purchase amount?
- Which categories have the highest sales volume?
- How does customer behavior vary across different segments?

### 4. Power BI Dashboard

Created an interactive dashboard containing:

- Total Customers
- Average Purchase Amount
- Average Review Rating
- Subscription Status
- Revenue by Category
- Sales by Category
- Revenue/Sales by Age Group

---

## 📊 Key Dashboard Metrics

| KPI | Value |
|---|---:|
| Total Customers | ~4K |
| Average Purchase Amount | **$59.76** |
| Average Review Rating | **3.75** |
| Subscribers | **27%** |
| Non-Subscribers | **73%** |

> *Values shown above are based on the final dashboard used in the project.*

---

## 💡 Key Insights

### 1. Low Subscription Adoption

Only **27% of customers were subscribed**, while **73% were non-subscribers**.

This indicates an opportunity to investigate why existing customers are not adopting the subscription program.

### 2. Category Performance

Revenue and sales volume do not necessarily tell the same story.

A category can sell more items while generating less revenue, while another category can sell fewer items but contribute more revenue.

Therefore, both **sales volume and revenue** were analyzed.

### 3. Customer Segmentation

Customer purchasing patterns vary across demographic segments.

Analyzing factors such as age, gender, category preference, and subscription status can help businesses create more targeted strategies.

---

## 🎯 Business Recommendations

Based on the analysis, potential strategies include:

- Investigate reasons behind low subscription adoption.
- Compare spending and purchase frequency between subscribers and non-subscribers.
- Test targeted subscription benefits and incentives.
- Use cross-selling strategies between product categories.
- Create customer-segment-specific marketing campaigns.
- Validate major recommendations through controlled experiments such as **A/B testing**.

> These recommendations are treated as business hypotheses to investigate/test rather than claims of causation.

---

## 📈 Power BI Dashboard

![Power BI Dashboard]
("Customer.pbix")

---

## 📁 Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── 📓 index.ipynb
├── 📊 PowerBI_Dashboard: Customer.pbix
├── 📑 Documentation_Project_Shopping_Behavior.docx ⭐⭐⭐⭐
├── 📄 customer_shopping.csv

You would like to add something, have suggestions or just wanna give advice
drop me here : dishabpps@gmail.com

--👩🏻‍💻DISHA
│   
└── README.md
