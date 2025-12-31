

# 👕 Men's T-Shirt Sales Analysis – Power BI Dashboard

### Dashboard Link: https://app.powerbi.com/Redirect?action=OpenReport&appId=c3287edf-719f-40d3-a3a1-de1025043674&reportObjectId=c0cf990a-18cb-4da2-ba8b-e71414557bcc&ctid=ea8ae8e0-4ea9-4d36-801d-0eee370d9e5f&reportPage=20e088c75b5ad75d0e21&pbi_source=appShareLink&portalSessionId=4271acbf-57ff-4839-8d0e-a281c2f1b36a

## 📌 Project Overview
This project analyzes **Men’s T-shirt sales data** using **Azure SQL Database** as the data source and **Power BI** for reporting and visualization.  
The dashboard provides actionable insights into sales performance, product demand, pricing effectiveness, and customer preferences to support better merchandising and inventory decisions.

---

## 🎯 Problem Statement
Retail apparel businesses often struggle to identify:
- Which T-shirt categories drive the highest revenue
- Optimal price ranges that maximize sales volume
- Size and color preferences impacting demand
- Underperforming products contributing to inventory inefficiencies

**The goal of this project is to:**
- Analyze sales performance across product attributes
- Identify demand patterns by size, color, and price
- Understand revenue contribution by category
- Enable data-driven decisions for pricing, inventory, and promotions

---

## 🗂️ Data Source
- **Primary Source:** Azure SQL Database  
- **Dataset:** Men’s T-shirt Sales Data  
- **Visualization Tool:** Power BI Desktop  

### Key Attributes Analyzed
- Product category and brand  
- Size and color  
- Unit price and discount  
- Quantity sold  
- Total sales revenue  
- Customer ratings (if available)

---

## 🔍 Data Analysis Steps

### 1. Data Ingestion
- Connected Power BI directly to **Azure SQL Database**.
- Imported transactional sales data into Power BI.

### 2. Data Cleaning & Transformation
- Removed duplicate and null records.
- Standardized categorical fields (size, color, category).
- Ensured correct data types for price, quantity, and revenue.
- Created calculated columns:
  - Total sales = Price × Quantity
  - Discounted price (where applicable)

### 3. Data Modeling
- Built a star-schema style model for efficient analysis.
- Created DAX measures for:
  - Total revenue
  - Average selling price
  - Units sold
  - Revenue contribution %

### 4. Exploratory Analysis
- Sales distribution across sizes and colors.
- Price vs quantity relationship.
- Identification of top-selling and low-performing products.

### 5. Dashboard Development
- Interactive slicers for category, size, and color.
- KPI cards for revenue, units sold, and average price.
- Bar and column charts for product and attribute comparison.

---

## 📊 Key Insights from the Dashboard

### 1. Revenue Concentration
- A small subset of T-shirt categories contributes a **major share of total revenue**, indicating strong product concentration.
- Premium-priced products generate higher revenue despite lower sales volume.

### 2. Size Demand Pattern
- **Medium (M) and Large (L) sizes** account for the highest sales volume.
- Extreme sizes (XS, XXL) show consistently lower demand, suggesting inventory optimization opportunities.

### 3. Color Preferences
- Neutral colors such as **Black, White, and Navy** dominate sales across all categories.
- Bright or niche colors have lower turnover and higher inventory risk.

### 4. Pricing Effectiveness
- Products priced in the **mid-range** achieve the highest unit sales.
- Heavy discounts increase volume but reduce overall revenue efficiency.

### 5. Product Performance
- Top-performing products combine:
  - Competitive pricing
  - Popular sizes
  - Neutral colors
- Underperforming SKUs show low rotation regardless of discounts.

---

## 💼 Business Value
- Helps retailers **optimize inventory** by focusing on high-demand sizes and colors.
- Supports **pricing strategy refinement** based on sales elasticity.
- Enables identification of **low-performing products** for discontinuation or redesign.
- Demonstrates end-to-end BI capability: Azure SQL → Power BI → Business Insights.

---

## 🛠️ Tools & Technologies
- **Azure SQL Database** – Data storage and querying  
- **Power BI Desktop** – Data modeling and visualization  
- **DAX** – Measures and business logic  

---

## 📁 Project Files
- `Azure_PowerBI_men_tshirt.pbix` – Power BI dashboard  
- `Men Tshirt.csv` – Source sales dataset  

---

## 🚀 Future Enhancements
- Customer segmentation analysis
- Seasonality and trend forecasting
- Profitability analysis using cost data
- Integration with real-time sales feeds

---

**Author:** Aditya Vijay  
**Domain:** Data Analytics | Business Intelligence  
