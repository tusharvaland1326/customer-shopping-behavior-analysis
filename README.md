# Customer Shopping Behavior Analysis

## 📊 Project Overview

This project analyses customer shopping behaviour to identify purchasing patterns, customer segments, product performance, and business opportunities.

The analysis uses **3,900 customer transactions and 18 variables**, covering customer demographics, product information, purchase amounts, payment methods, subscription status, shipping preferences, and review ratings.

The project demonstrates an end-to-end data analytics workflow using **Python, PostgreSQL/SQL, and Power BI**.

---

## 🎯 Project Objectives

- Analyse customer purchasing behaviour and spending patterns
- Clean and prepare the raw dataset for analysis
- Perform exploratory data analysis using Python
- Answer business questions using SQL
- Build an interactive Power BI dashboard
- Identify customer and product trends
- Generate actionable business recommendations

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data cleaning and exploratory data analysis |
| Pandas | Data manipulation and preprocessing |
| PostgreSQL | Database analysis and SQL queries |
| SQL | Business and customer behaviour analysis |
| pgAdmin 4 | SQL query execution |
| Power BI | Interactive dashboard and visualisation |
| Jupyter Notebook | Python analysis and documentation |
| Git & GitHub | Project version control and portfolio hosting |

---

## 🔄 Project Workflow

### 1. Data Collection

Loaded the customer shopping behaviour dataset containing **3,900 transaction records**.

### 2. Data Cleaning

- Inspected the dataset using Pandas
- Identified missing values in `Review Rating`
- Replaced missing review ratings using the median
- Standardised column names using snake_case
- Removed redundant columns
- Created an `Age Group` feature for customer segmentation

### 3. Exploratory Data Analysis

- Analysed customer demographics
- Examined product category performance
- Analysed purchase amounts and customer ratings
- Compared subscribers and non-subscribers
- Investigated customer purchasing patterns

### 4. SQL Business Analysis

The cleaned dataset was imported into PostgreSQL.

SQL queries were used to investigate:

- Revenue by gender
- Product performance
- Customer segments
- Customer ratings
- Discount behaviour
- Subscription behaviour
- High-spending customers

### 5. Power BI Dashboard

An interactive Power BI dashboard was developed to visualise customer behaviour and sales performance.

The dashboard includes KPIs, charts, and filters for exploring the dataset.

---

## 📈 Key Findings

- **3,900** customer transactions were analysed.
- **Clothing** was the highest-selling product category.
- **Young Adults** represented the largest customer segment.
- The **average purchase amount was approximately £60**.
- The **average customer review rating was 3.75**.
- **Male customers generated higher total revenue** than female customers.
- **Gloves, Sandals, and Boots** were among the highest-rated products.
- **Non-subscribers generated higher total revenue**, mainly because they represented a larger customer base.
- High-spending customers who also received discounts were identified as potential targets for loyalty programmes.

---

## 💡 Business Recommendations

### 1. Increase Subscription Membership

Offer exclusive benefits, personalised offers, and member-only promotions to encourage more customers to subscribe.

### 2. Promote Highly Rated Products

Use targeted marketing campaigns to promote products with strong customer ratings, such as Gloves, Sandals, and Boots.

### 3. Strengthen Customer Loyalty

Introduce loyalty programmes and personalised discounts for high-value and repeat customers.

### 4. Personalise Product Recommendations

Use customer purchasing behaviour, product preferences, and spending patterns to provide more relevant product recommendations.

### 5. Improve Customer Retention

Use customer segmentation and personalised promotions to improve engagement and encourage repeat purchases.

---

## 📊 Power BI Dashboard

The Power BI dashboard provides an interactive view of customer behaviour and sales performance.

### Dashboard Includes

- Total Customers
- Average Purchase Amount
- Average Review Rating
- Sales by Category
- Revenue by Age Group
- Gender Distribution
- Subscription Status
- Shipping Type
- Customer Purchasing Behaviour

> **Note:** Open the `.pbix` file using Microsoft Power BI Desktop to interact with the dashboard.

---

## 📁 Repository Structure

```text
customer-shopping-behavior-analysis/
│
├── customer_shopping_behavior.csv
├── Customer_Shopping_Behavior_Analysis.ipynb
├── customer_behavior_queries.sql
├── customer_shopping_behavior_dashboard.pbix
├── customer shopping behavior analysispdf.pdf
├── customer shopping behavior analysis report.pdf
├── Customer.pdf
└── README.md
