# 📊Retail-Insights-Hub-in-Power-BI
Retail Insights Hub is a Power BI project analyzing 2011 online retail data. The dashboard highlights monthly revenue trends, top countries and customers by revenue, and product demand by geography. Using line, clustered column, and map visuals, it provides clear insights into seasonal sales, key markets, loyal customers, and growth opportunities.

## 📌 Project Overview
Retail Insights Hub is a Power BI project analyzing an online retail dataset from 2011.  
The dashboard provides actionable insights into **sales performance, customer behavior, and product demand**, helping CEO & CMO identify seasonal trends, high-performing regions, and opportunities for growth.

---

## 📂 Dataset Description
- **Source:** Online retail dataset (Excel)  
- **Key Columns:** Invoice No, Stock Code, Customer ID, Product Description, Quantity, Unit Price, Country  
- **Scope:** Transactions filtered to the year 2011  

---

## 🛠️ Data Cleaning & Preparation
Performed in **Power Query Editor**:
- Removed invalid records (negative quantities, zero/negative unit prices)  
- Filtered invoice dates after **1-Jan-2011**  
- Replaced null product descriptions with blanks  
- Converted Customer ID to integer type  
- Final dataset: unit prices > 0, quantities ≥ 1, invoice dates in 2011 only  

---

## 📈 Dashboard Visuals
- **Monthly Revenue (Line Chart):** Shows revenue trends across 2011, peaks in October & November  
- **Top 10 Countries by Revenue (Clustered Column Chart):** Excluding UK, highlights Netherlands, Eire, Germany  
- **Top 10 Customers by Revenue (Clustered Column Chart):** Identifies most valuable customers driving majority of revenue  
- **Product Demand by Country (Map):** Excluding UK, highlights Europe, Asia, and Australia  

---

## 💡 Business Insights
- Seasonal revenue peaks → plan resources accordingly  
- High-performing countries → prioritize marketing spend  
- Key customers → strengthen loyalty programs  
- Geographic demand → identify expansion opportunities  

---

## ✅ Conclusion
The Retail Insights Hub dashboard provides a clear view of company performance in 2011.  
It helps leadership make informed decisions about **resource allocation, marketing focus, customer engagement, and market expansion**.

---

## 📎 Documentation
For detailed project documentation, see:   
- **PDF File:** `Retail_Insights_Hub_Documentation.pdf`  

---

## 📂 Repository Structure
- 📊 Online retail sales visuals.pbix  → Power BI dashboard file 
- 📑 Online Retail.xlsx → Dataset (Excel)
- 📄 Retail_Insights_Hub_Documentation.pdf → Detailed project documentation (PDF)  
- 📝 README.md → Project overview and usage guide
- 📸 Visuals →                            
              - Monthly revenue trends.png
              - Country-level revenue comparision.png
              - Top 10 customers by revenue.png
              - Product demand by Country.png

---

## 🚀 How to Use
1. Download the dataset and `.pbix` file from this repository.  
2. Open the `.pbix` file in **Power BI Desktop**.  
3. Explore the dashboard visuals and insights.  

