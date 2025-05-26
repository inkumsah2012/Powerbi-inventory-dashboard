# 🧮 Inventory Performance Dashboard using Power BI

## 📊 Project Overview

This project visualizes and analyzes **inventory consumption trends, purchasing patterns, and stock alerts** using Power BI. It is built from a real-world **E-Commerce Inventory Dataset** sourced from [Kaggle](https://www.kaggle.com/). The dashboard helps businesses make data-driven decisions by providing a **comprehensive overview of inventory flow, low stock alerts, and location-based performance**.

## 📁 Dataset Description

The dataset includes four key tables that form a star schema:
- `Fact_Inventory.csv` – Inventory transactions including purchase, consumption, and ending quantity
- `Dim_Date.csv` – Date dimension used for time-based analysis
- `Dim_Location.csv` – Information on store locations
- `Dim_Ingredient.csv` – List of food/ingredient items

Time period covered: **2018 - 2021**  
Total store locations: **12**

## 📈 Dashboard Pages

### 1. Executive Summary Dashboard
- 🔹 Total Purchase vs Total Consumption
- 🔹 Inventory Turnover Ratio
- 🔹 Average Ending Quantity
- 🔹 Low Stock / Reorder Alert (⚠️)
- 🔹 Monthly Consumption Trend
- 🔹 Inventory Status Breakdown (Normal / Overstock / Shortage)

### 2. Ingredient Analytics Dashboard
- 📦 Track usage of top ingredients over time
- 📉 Compare purchase vs. consumption per ingredient
- 📌 Identify the top 10 most consumed ingredients

### 3. Location Performance Dashboard
- 📍 Compare inventory performance across locations
- 🌆 Identify top performing locations by consumption
- 🧾 Monitor inventory status per location

### 4. Forecast Consumption Trend
- 🔮 Forecast future consumption trends using Power BI's built-in analytics
- 📅 Interactive filters to explore trends by date

## ⚙️ Power BI Features Used
- Data Modeling (Star Schema)
- DAX Measures:
  - Total Purchase
  - Total Consumption
  - Inventory Turnover Ratio
  - Avg. Ending Quantity
  - Reorder Alert Flag
- Time Intelligence
- Forecasting with Analytics Pane
- Slicers and Drill-Through Filters

## 💡 Insights Gained
- Most ingredients are **consumed slightly less than purchased**, indicating manageable wastage.
- ⚠️ **Low stock alerts** help identify ingredients at risk of shortage.
- Certain locations (e.g. **Vancouver**) have **higher consumption trends** and may require more frequent stock checks.
- Overall inventory appears to be well-managed with **minimal overstocking**.

## 🛠️ Tools & Technologies
- Power BI Desktop
- DAX (Data Analysis Expressions)
- Microsoft Excel (for data cleaning)
- GitHub (for version control and project sharing)

## 📂 Project Files
- 📄 `Fact_Inventory.csv` – Raw fact table
- 📄 `Dim_Date.csv`, `Dim_Ingredient.csv`, `Dim_Location.csv` – Dimension tables
- 📊 `.pbix` file – Power BI dashboard

## 🚀 Getting Started
To explore the dashboard:
1. Download the `.pbix` file from this repository
2. Open with Power BI Desktop
3. Connect to CSV files (if needed) using **Data Source Settings**

## 👨‍💻 Author
**Emmanuel Yaw Inkum**  
Data Scientist | Data Analyst  
📧 [LinkedIn Profile](https://linkedin.com/in/emmanuel-yaw-inkum-769bb1125)
