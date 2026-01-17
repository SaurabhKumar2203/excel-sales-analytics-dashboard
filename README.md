# 📊 Retail Sales Analytics Dashboard

## 🚀 Project Overview
This project transforms raw, messy sales records into a dynamic **Executive Command Center**. The goal was to provide the Sales Director with a "one-screen" view of performance across 3 major cities, enabling data-driven decisions on inventory and marketing.

<img width="1521" height="935" alt="dashboard-view" src="https://github.com/user-attachments/assets/4fb83dcf-ec53-45eb-a8ce-8ca4863a686c" />

## 💼 Business Problem
The sales team was struggling with:
* **Data Silos:** Sales data was scattered in unformatted spreadsheets.
* **Lack of Visibility:** No easy way to track "Profit Margin" vs "Raw Revenue."
* **Static Reporting:** Managers couldn't filter by Month or Category without asking an analyst.

## 🛠️ The Solution
I built an interactive Excel Dashboard featuring:
* **ETL Process:** Cleaned inconsistent city names (e.g., "mumbai" vs "Mumbai") using `PROPER()` and standardized date formats.
* **Data Modeling:** Created an automated "Engine" sheet using **Pivot Tables** to aggregate millions in revenue.
* **Advanced Analytics:** Calculated **Profit Margin %** using Custom Calculated Fields.
* **UX/UI Design:** Integrated **Slicers** and **Timelines** for real-time filtering (No VBA required).
* **Combo Charts:** Visualized Revenue (Bars) and Margin % (Line) on a dual-axis chart to spot efficiency trends.

## 📉 Key Insights
* **Bangalore** is the most efficient city with a **30% Profit Margin**, despite having lower total revenue than Delhi.
* **Revenue Trend:** There is a noticeable dip in February; investigation into stock levels recommended.
* **Electronics** remains the dominant category, driving 70% of total sales.

## 💻 Technical Skills Used
* **Excel Tables:** For dynamic data ranges.
* **Pivot Tables & Charts:** For aggregation and visualization.
* **GETPIVOTDATA:** For building custom scorecard KPIs.
* **Data Cleaning:** Text formulas and conditional logic.

---
*Created by Saurabh Kumar*
