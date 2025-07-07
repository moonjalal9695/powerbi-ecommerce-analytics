# 🛒 E-commerce Analytics Dashboard

## 🔍 Problem Statement
This project aims to analyze an e-commerce dataset to extract meaningful insights that can help stakeholders make data-driven business decisions. The final result is a multi-page Power BI dashboard that visualizes KPIs, customer behavior, and sales performance.

---

## 🧰 Tech Stack

- **Python** (Pandas, Matplotlib, Seaborn) – for data cleaning and EDA
- **PostgreSQL** – for querying and storing cleaned data
- **Power BI** (DAX) – for building interactive dashboards

---

## 📊 Methodology

1. **Data Ingestion**  
   Collected and imported a raw e-commerce dataset (.csv) into Jupyter Notebook.

2. **Exploratory Data Analysis (EDA)**  
   Cleaned null values, parsed dates, handled duplicates, and visualized trends using `EDA.ipynb`.

3. **SQL Queries**  
   Loaded cleaned data into PostgreSQL and executed SQL scripts to extract metrics like:
   - Top-selling categories
   - Repeat customer ratio
   - Regional sales trends

4. **Power BI Dashboarding**  
   Imported SQL tables into Power BI, applied data modeling, built slicers, and used DAX measures to show:
   - Total Sales
   - Customer Segmentation (RFM)
   - Monthly Revenue Trends
   - Top 10 Products

---



---

## 🔑 Key Insights

1. 🏆 **Top Product Category:** Electronics generated the highest revenue, contributing 28% of total sales.
2. 🌍 **Regional Trends:** The South region has the highest customer base but lower conversion rates.
3. 🔁 **Customer Loyalty:** 60% of customers made repeat purchases within the last quarter.
4. ⏰ **Sales Spike:** There was a noticeable spike in sales during holiday campaigns in November and December.

---

## 📁 File Overview

| File/Folder            | Description                                    |
|------------------------|------------------------------------------------|
| `notebooks/EDA.ipynb`  | Python script for data exploration             |
| `powerbi/*.pbix`       | Power BI dashboard file                        |
| `.gitignore`           | Files to ignore during Git versioning          |
| `README.md`            | Project documentation                          |

---


