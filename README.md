# 🌍 Global Superstore Sales Performance & Forecasting Dashboard

A comprehensive, interactive business intelligence solution built using **Power BI** to analyze sales performance, regional distributions, customer behavior, and future sales trends for a global retail enterprise.

---

## 📊 Project Overview
This project provides deep-dive analytics into global retail data (`superstore_enhanced`), enabling stakeholders to track key performance indicators (KPIs), identify top-performing product categories, monitor customer segments, and leverage forecasting models for strategic decision-making.

---

## 🚀 Key Dashboard Pages & Features

### 1. Sales Performance Overview
* **KPI Cards:** Total Customers (793), Average Order Value ($459.48), Total Profit ($263.12K), Total Orders (5K), and Total Sales ($2.26M).
* **Time-Series Analysis:** Visualizes how sales evolved over time with clear peak tracking.
* **Category & Customer Insights:** Highlights top-performing product categories (Technology leads in total sales) and identifies the Top 10 customers by revenue.
* **Geographical Distribution:** Interactive map and regional breakdown (West, East, Central, South) showing geographical sales concentration.
* **Smart Insights Panel:** Automated summary of key takeaways and critical performance drivers.

### 2. Sales Trend and Forecast Analysis
* **Quarterly & Monthly Seasonality:** Breaks down quarterly sales performance and monthly cyclical trends.
* **Predictive Forecasting:** Historical sales trends coupled with advanced forecasting to project short-term future demand.
* **Category Growth Forecast:** Forward-looking projections across Technology, Furniture, and Office Supplies.
* **Regional Forecast Share & Breakdown:** Detailed data grids and donut charts analyzing predicted sales distribution by region across multiple years (2015–2018).

---

## ⚙️ Data Model & Structure
The relational data model is structured using star-schema design principles:
* `superstore_enhanced` (Fact Table)
* `Dim_Customers` (Dimension Table)
* `Dim_Date` (Dimension Table)
* `Dim_Locations` (Dimension Table)
* `Dim_Products` (Dimension Table)
* `Growth Rate` (Calculated Measures/Metrics)

---

## 🛠️ Tools & Technologies Used
* **Power BI Desktop:** For data modeling, DAX measures, data transformation (Power Query), and interactive report design.
* **Git & GitHub:** For version control and project documentation.

---

## 📁 How to View the Project
1. Clone or download this repository to your local machine.
2. Ensure you have **Power BI Desktop** installed.
3. Open the `.pbix` file included in this repository to explore the interactive dashboards and data models.

---
