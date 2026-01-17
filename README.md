# 📊 Retail Sales Analytics Dashboard

## 🚀 Project Overview
This project transforms raw, messy sales records into a dynamic **Executive Command Center**. The goal was to provide the Sales Director with a "one-screen" view of performance across 3 major cities, enabling data-driven decisions on inventory and marketing.

### 🏆 The Final Dashboard
<img width="100%" alt="dashboard-view" src="https://github.com/user-attachments/assets/4fb83dcf-ec53-45eb-a8ce-8ca4863a686c" />

---

## 💼 Business Problem
The sales team was struggling with:
* **Data Silos:** Sales data was scattered in unformatted spreadsheets with inconsistent naming conventions.
* **Lack of Visibility:** No easy way to track "Profit Margin" vs "Raw Revenue" in real-time.
* **Static Reporting:** Managers couldn't filter by Month or Category without asking an analyst to rebuild the report.

---

## 🛠️ The Process: From Chaos to Control

### Step 1: Data Cleaning (ETL)
The raw data contained inconsistent capitalization (e.g., "mumbai", "MUMBAI") and missing calculations.
* **Action:** Used `PROPER()` to standardize city names and calculated **Profit** (`Revenue - Cost`) and **Margin %** (`Profit / Revenue`) before analysis.

<img width="992" height="935" alt="raw-data" src="https://github.com/user-attachments/assets/a6f9ecbe-1524-4b80-b3a4-2a004d20d418" />

### Step 2: The "Engine" (Pivot Tables)
Instead of building charts directly on raw data, I created a dedicated **Engine Sheet** to handle aggregations. This ensures the dashboard stays lightweight and fast.
* **Action:** Built two separate Pivot Tables (Geographic & Time-series) and linked them via Report Connections.

  
<img width="1200" height="725" alt="pivot-logic" src="https://github.com/user-attachments/assets/c1c3612f-aa5d-4b0c-a4cb-a60ea31addf8" />

---

## 📉 Key Insights Discovered
* **Efficiency Win:** **Bangalore** is the most efficient city with a **30% Profit Margin**, despite having lower total revenue than Delhi.
* **Seasonal Trend:** There is a noticeable dip in February revenue; investigation into stock levels is recommended.
* **Category Dominance:** **Electronics** remains the dominant category, driving 70% of total sales.

---

## 💻 Technical Skills Used
* **Excel Tables:** For dynamic data ranges (auto-updating source data).
* **Pivot Tables & Charts:** For aggregation and visualization.
* **GETPIVOTDATA Function:** For building custom scorecard KPIs that don't break when data changes.
* **Slicers & Timelines:** Connected to multiple objects for a unified filtering experience.
* **Combo Charts:** Visualized Revenue (Bars) and Margin % (Line) on a dual-axis chart.

---
*Created by Saurabh Kumar*
