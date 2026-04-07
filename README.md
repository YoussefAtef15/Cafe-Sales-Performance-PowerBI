# ☕ Cafe Sales Performance Analysis | Power BI End-to-End Solution

## 📌 Project Overview
This project is an end-to-end **Business Intelligence solution** designed to transform raw, inconsistent cafe transactional data into a highly interactive and insightful Power BI dashboard. 

The primary objective is to solve a real-world business problem: extracting actionable insights from "dirty" data to track key performance indicators (KPIs), optimize profit margins, and understand customer purchasing behaviors.

## 🚀 Business Problem & Solution
* **The Challenge:** The initial dataset (`dirty_cafe_sales.csv`) was unstructured, containing missing values, incorrect data types, and formatting errors, making it impossible to derive accurate financial metrics directly.
* **The Solution:** I developed a complete ETL pipeline and a robust relational data model to clean the data and visualize critical metrics, enabling stakeholders to make data-driven decisions instantly.

## 🧠 Technical Highlights & Methodology

### 1. Data Cleaning & ETL (Power Query)
* **Extraction:** Imported data from raw CSV files.
* **Deep Cleaning:** Handled missing (`null`) and `UNKNOWN` values, corrected pricing anomalies, and standardized data formats.
* **Feature Engineering:** Created calculated columns to extract deeper analytical insights.

### 2. Data Modeling (Star Schema)
* **Architecture:** Architected an optimized relational data model connecting the central Fact Table (Transactions) with supporting Dimension Tables (Products, Dates, Locations).
* **Relationships:** Managed active and inactive relationships, ensuring precise table connections for seamless cross-filtering.

### 3. Advanced DAX & Metrics
* **Dynamic KPIs:** Authored optimized DAX measures to track overall business performance.
* **Deep Analytics:** Developed complex calculations for **Profit Margins**, **Revenue**, and **Score Analytics**.
* **Trend Analysis:** Implemented Time-Intelligence functions to monitor performance over specific periods.

### 4. Dashboard Design & Visualization
* **UI/UX Design:** Crafted an intuitive, user-friendly layout focusing on effective data storytelling.
* **Interactivity:** Implemented dynamic slicers, tooltips, and cross-highlighting to allow users to drill down into specific dates, payment methods, or product categories.
* **Styling:** Applied a clean, consistent color palette and formatting structure for a professional presentation.

## 📊 Dashboard Preview
*(A comprehensive view of the final interactive dashboard)*

![Cafe Sales Dashboard](Screenshots/dashboard-preview.png)

## 💡 Key Insights
* **Top Selling Product:** [اكتب هنا المنتج] drives the highest revenue.
* **Peak Sales Periods:** [اكتب هنا الوقت أو اليوم] experiences the highest foot traffic and sales volume.
* **Payment Preferences:** [اكتب هنا طريقة الدفع] is the most frequently used method among customers.
* **Profit Margins:** Achieved a clear view of profit margins, highlighting [اكتب هنا استنتاج عن الأرباح].

## 💻 Tech Stack
* **Tools:** Power BI
* **Languages:** DAX, Power Query (M)
* **Core Concepts:** Data Modeling (Star Schema), ETL, Data Visualization, Business Intelligence
