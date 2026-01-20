# 🚗 Car Sales Insights: Interactive Sales Performance Dashboard

A dynamic and interactive Power BI dashboard designed to analyze automotive sales trends, track key performance indicators (KPIs), and provide data-driven insights into market performance, vehicle types, and manufacturer sales.

## 📌 Project Overview
The **Car Sales Insights Dashboard** provides a comprehensive view of sales data to help stakeholders understand market dynamics. It focuses on identifying top-performing car brands, sales distribution across different body styles (Sedan, SUV, etc.), and year-over-year growth patterns.

**Purpose:** This tool is built for sales managers, dealership owners, and market analysts to monitor sales targets, optimize inventory based on popular models, and evaluate pricing strategies.

## 🛠️ Tech Stack
The dashboard was built using the following tools and technologies:
* **📊 Power BI Desktop** – The core platform for data visualization and report design.
* **📂 Power Query** – Used for ETL processes (Cleaning, transforming, and formatting raw car sales data).
* **🧠 DAX (Data Analysis Expressions)** – Implemented for complex measures such as *Total Sales, Year-to-Date (YTD) Growth, and Average Price per Unit*.
* **📝 Data Modeling** – Established a Star Schema/Snowflake schema to connect sales transactions with vehicle details and date tables.
* **📁 File Format** – Developed as `.pbit` (Template) and `.pbix` for full report access.

## 📊 Data Source
* **Source:** Car Sales Dataset (Kaggle).
* **Details:** The dataset includes information on hundreds of car sales transactions, including:
    * **Vehicle Info:** Manufacturer, Model, Body Style, Engine, and Transmission.
    * **Sales Info:** Sale Price, Date of Sale, Dealer region, and Color.

## ✨ Key Features & Highlights

### 🎯 Business Problem
The automotive market is highly competitive. Dealerships often struggle to:
1.  Identify which car models are trending in specific periods.
2.  Monitor if they are meeting monthly or yearly sales targets.
3.  Understand the price-point sensitivity of customers across different car types.

### 🚀 Goal of the Dashboard
To deliver an actionable visual tool that:
* Tracks **Total Revenue** and **Quantity Sold**.
* Analyzes sales performance by **Manufacturer** and **Model**.
* Visualizes geographical sales distribution or dealer performance.

### 🔍 Walkthrough of Key Visuals
* **Executive KPIs:** High-level cards showing Total Sales, Average Price, and Units Sold.
* **Sales Trend (Line Chart):** Displays sales fluctuations over months/years to identify seasonal trends.
* **Market Share by Brand (Donut/Pie Chart):** Shows the dominance of manufacturers like Toyota, Ford, etc.
* **Body Style Analysis (Bar Chart):** Compares sales between SUVs, Sedans, Hatchbacks, and Luxury cars.
* **Top Models Table:** A detailed breakdown of the best-selling models with their respective revenue.

## 💡 Business Impact & Insights
* **Inventory Optimization:** Dealerships can stock more of the "Best Selling" body styles (e.g., SUVs) based on the data.
* **Pricing Strategy:** Analysis of average sale prices helps in setting competitive price points.
* **Performance Tracking:** Sales teams can identify underperforming regions or brands and take corrective actions.

## 🔍 Walkthrough of Key Visuals

### 1. Main Overview Dashboard
![Main Dashboard View](https://github.com/hossamH9/Car-Sales-Dashboards/blob/main/Screenshot%202026-01-20%20162931.png)
*هنا بنعرض نظرة عامة على إجمالي المبيعات وأداء البراندات المختلفة.*

### 2. Main home Dashboard
![Sales Trends](https://github.com/hossamH9/Car-Sales-Dashboards/blob/main/Screenshot%202026-01-20%20163003.png)
*الرسم البياني ده بيوضح تطور المبيعات شهرياً وتأثير المواسم على الشراء.*

 

---
*Created by [Your Name/GitHub Username]*
