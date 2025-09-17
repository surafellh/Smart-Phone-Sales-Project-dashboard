# 📊 Smartphone Sales Report – Power BI Dashboard

## 📌 Project Overview
This project transforms smartphone sales data into **actionable insights** using Power BI.  
The dataset includes **366 transactions across 19 smartphone models from 5 brands**, enriched with product details, locations, and a full date hierarchy.  

The dashboard answers key business questions such as:  
- Which brands and models are driving sales?  
- How do sales trends change month-to-month?  
- Which regions and customer segments are most profitable?  
- What strategies can maximize revenue and growth?  

---

## 🗂 Dataset
- **Size**: 366 rows of sales data  
- **Brands**: Apple, Samsung, OnePlus, Google, Xiaomi  
- **Products**: 19 different smartphone models  
- **Tables**:
  - `Fact_Sales`: sales transactions (units sold, revenue, date, customer, location, channel)  
  - `Dim_Products`: brand, model, OS, storage, color  
  - `Dim_Model_Image`: product specs (RAM, CPU, display, battery, etc.)  
  - `Dim_Locations`: city, country, latitude/longitude  
  - `Dim_Calendar`: full date hierarchy for time intelligence  
  - Supporting KPI/calculation tables  

---

## ⚡ Approach
- Built a **star schema** model for clean relationships  
- Created **parameters** for dynamic filtering (brand/region)  
- Applied **time intelligence** (month-on-month, seasonal analysis)  
- Designed **interactive visuals** (KPIs, bar/line charts, maps) for clarity  
- Enabled **drill-downs** for exploration from summary → detail  

---

## 💡 Key Insights
🎥 **Video Demo of Dashboard Interactivity**  

![Dashboard Demo](demo.gif)  

- 📈 A few brands dominate sales, but smaller brands are growing quickly  
- ⏳ Clear seasonal dips highlight when to adjust inventory and marketing  
- 🌍 Region-level analysis shows underperforming markets with hidden potential  
- 👥 Age groups 26–33 and 42–49 generated the highest revenue segments  
- 🛒 Online channels accounted for **62%** of total revenue, but retail still plays a big role  

---

## 📸 Dashboard Snapshots

### 1️⃣ Overview Page  
- Executive summary of sales performance  
- Total revenue, units sold, average price  
- Revenue split by age group, gender, channel, payment type  
- High-level view of **brand and country performance**  

### 2️⃣ Brand Performance Page  
- Revenue by **brand and model**  
- Month-on-month brand comparison  
- Top-performing model details (RAM, CPU, price, etc.)  
- Gartner-inspired “quadrant” chart to position brand performance  

### 3️⃣ Regional Performance Page  
- Revenue by **country and city**  
- Regional contribution to overall sales  
- Average price comparison across brands  
- Storage size contribution to revenue  
- Customer demographics tied to location  

*(Insert your exported snapshots here, e.g. `overview.png`, `brand.png`, `region.png`)*  

---

## 🎯 Business Value
This dashboard enables decision-makers to:  
- Reallocate marketing toward fast-growing brands  
- Align supply with seasonal demand cycles  
- Expand into underperforming but high-potential regions  
- Optimize sales channels and payment strategies  

---

## 🛠 Tools & Technologies
- **Power BI Desktop**  
- **DAX** (KPIs, time intelligence)  
- **Excel/CSV** dataset  
- **Star schema** data modeling  

---

## 🚀 How to Use
1. Clone this repository  
2. Open the `.pbix` file in Power BI Desktop  
3. Explore using filters, parameters, and drill-downs  

---

📂 This project demonstrates how **structured data + Power BI** can generate insights that directly support strategic business decisions.

