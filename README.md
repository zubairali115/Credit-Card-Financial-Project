# 💳 Credit Card Analytics Dashboard (Excel + PostgreSQL + Power BI)

## 📌 Project Overview

This project focuses on analyzing **credit card customer behavior and business performance** using a modern data analytics workflow.
The complete pipeline includes **Excel (data preparation) → PostgreSQL (database) → Power BI (dashboard & insights)**.

The goal of this project is to transform raw credit card data into **actionable insights** that help understand customer spending patterns, revenue drivers, churn risk, and overall business performance.

## 🧠 Problem Statement

Financial institutions generate large volumes of customer and transaction data.
Without proper analytics, it becomes difficult to answer questions like:

* Who are the most valuable customers?
* Which card category generates the most revenue?
* Which customers are at risk of churn?
* What spending categories drive profit?

This project solves these problems using a complete **data analytics pipeline**.

---

## 🛠️ Tech Stack

| Tool           | Purpose                                |
| -------------- | -------------------------------------- |
| **Excel**      | Data cleaning & preprocessing          |
| **PostgreSQL** | Data storage & querying                |
| **Power BI**   | Data modeling & interactive dashboards |

---

## 🔄 Data Pipeline Workflow

1. **Data Cleaning in Excel**

   * Removed duplicates & null values
   * Standardized column names and formats
   * Prepared structured tables for database import

2. **Database Creation in PostgreSQL**

   * Imported cleaned datasets into PostgreSQL
   * Wrote SQL queries for transformation and aggregation
   * Built relationships between tables

3. **Data Modeling in Power BI**

   * Connected Power BI to PostgreSQL database
   * Created relationships and star schema model
   * Developed DAX measures and KPIs

4. **Dashboard Development**

   * Built interactive reports for business insights
   * Added filters, slicers, and drill-down visuals

---

## 🗄️ Database Tables

Main table used in the project:

### `cc_detail`

Contains credit card customer information such as:

* Client number
* Card category
* Income group
* Education level
* Customer demographics
* Transaction & revenue data

---

## 📊 Key KPIs & Metrics

The dashboard focuses on major financial and customer metrics:

* 💰 Total Revenue
* 💳 Total Transactions
* 📈 Average Transaction Amount
* 👥 Customer Segmentation
* 🔁 Customer Churn Analysis
* 🏆 Top Spending Categories
* 📌 Revenue by Card Category
* 📍 Demographic Insights

---

## 📈 Dashboard Insights

The Power BI dashboard answers important business questions:

### Customer Insights

* Identify high-value customers
* Analyze income and education impact on spending
* Understand customer segmentation

### Revenue Insights

* Which card type generates the highest revenue
* Spending distribution across categories
* Monthly and yearly trends

### Risk & Retention Insights

* Detect churn patterns
* Identify customers with low engagement
* Support retention strategy decisions

---

## ✨ Features of Dashboard

* Interactive slicers and filters
* Dynamic KPIs
* Drill-down analysis
* Clean and professional UI
* Business-ready visual storytelling

---

## 🚀 How to Use This Project

1. Import the dataset into **PostgreSQL**
2. Connect **Power BI** to PostgreSQL database
3. Load the provided `.pbit` template
4. Refresh data to view the dashboard
   
---

## 🎯 Project Outcome

This project demonstrates:

* End-to-end data analytics workflow
* SQL + Power BI integration
* Real-world financial data analysis
* Business insight generation from raw data

---

## 👤 Author

**Zubair Ali**
Aspiring Data Analyst | Power BI | SQL | Excel

---

⭐ If you like this project, consider giving it a star!

