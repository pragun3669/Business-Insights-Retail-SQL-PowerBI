# 📊 Retail Sales Insights (SQL + Power BI)

This project delivers an end-to-end **retail sales analytics solution** using **SQL** for data processing and **Power BI** for visualization.  
The goal is to uncover **business insights** from raw transactional data — including sales trends, profitability, customer behavior, and product performance — to support better decision-making.  

---

## 🧾 Project Overview
The dataset used represents transactional sales records of a fictional retail store.  
The project workflow involves:  
1. **Data Cleaning & Transformation (SQL):** Checking for missing values, duplicates, aggregating KPIs.  
2. **Exploratory Analysis (SQL):** Writing queries to analyze sales, profit margins, shipping patterns, and customer segments.  
3. **Visualization (Power BI):** Building interactive dashboards with KPIs, charts, and filters for stakeholders.  

---

## 🛠️ Tools & Technologies
- **SQL Server / MySQL** → for data cleaning, aggregations, and trend analysis  
- **Power BI Desktop** → for dashboards and visual storytelling  
- **Excel/CSV Dataset** → as the raw source file  

---

## 📂 Dataset
The dataset contains ~10K rows of sales transactions with fields such as:  

| Column Name  | Description |
|--------------|-------------|
| `Order ID`   | Unique identifier for each order |
| `Order Date` | Date order was placed |
| `Ship Mode`  | Shipping type (Standard, Second Class, etc.) |
| `Customer ID`| Unique customer identifier |
| `Segment`    | Customer category (Consumer, Corporate, Home Office) |
| `Product`    | Product name and category |
| `Sales`      | Revenue generated |
| `Quantity`   | Units sold |
| `Discount`   | Discount % applied |
| `Profit`     | Profit earned/lost |

---

## ❓ Key Questions Explored
### ✅ Basic
- What are the total sales, profit, and order quantities?  
- How do sales vary by category, segment, and region?  

### 🔁 Intermediate
- Which products drive the most revenue/profit?  
- What is the impact of discounting on profitability?  
- Which shipping mode is most frequently used?  

### 🔍 Advanced
- Monthly growth rates (using SQL window functions)  
- Top/bottom products by profit in each region  
- Customers with only a single purchase (loyalty insight)  
- Profit margin % by product categories  

---

## 📈 Dashboard Highlights
- **Overall KPIs:** Total Sales, Total Profit, Total Orders  
- **Breakdowns:** By Region, Segment, Product Category  
- **Time-Series:** Monthly sales & profit trends  
- **Top/Bottom Analysis:** High-performing vs. loss-making products  
- **Interactivity:** Filters for region, year, and customer segment  

> 📍 Example dashboard screenshots are included in the repo.  

---

## 🔑 Insights Discovered
- 📦 Technology generates the highest sales, but Office Supplies has better profit margins.  
- 🌎 The West region leads in both sales and profit contribution.  
- 📉 Heavy discounts (>30%) often reduce profitability significantly.  
- 🚚 Standard Class is the most used shipping mode (~60% of orders).  
- 📅 Seasonal spikes in sales during November–December indicate holiday-driven demand.  

---

## 🏁 Conclusion
This project shows how SQL + Power BI can transform raw retail data into **actionable insights**.  
Findings highlight areas for **improving profitability**, **monitoring loss-making products**, and **optimizing sales strategies**.  

---

⭐ *If you find this project useful, feel free to star the repo!*  
