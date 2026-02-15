# Bike-Store-Sales-Analysis

# 🚴 Bike Store Sales Analysis | Power BI Dashboard

## 📌 Project Overview

This project presents an interactive **Power BI dashboard** built to analyze Bike Store sales data and uncover meaningful business insights related to revenue, profit, customers, products, and regional performance.

The goal of the project is to transform raw transactional data into a decision-making tool for business stakeholders.

## 🎯 Objectives

* Analyze overall sales performance across years, months, and quarters
* Identify top-performing product categories
* Understand customer demographics (Age group & Gender)
* Evaluate regional revenue distribution
* Track profit and cost trends
* Build an interactive report using slicers and filters

## 📊 Key KPIs

* **Total Revenue:** $85.27M
* **Total Profit:** $32.2M
* **Average Revenue:** $754.4
* **Average Order Quantity:** 11.9
* **Revenue per Unit:** $63.4
* **Average Unit Cost:** $267.3
* **Max Unit Price:** $3.58K

## 🧠 Business Insights

* Road Bikes generate the highest revenue among all categories
* Adults contribute the largest number of orders
* Revenue peaks during **February and April**
* Sales grew steadily till **2015** and slightly declined afterward
* California contributes the highest regional revenue share
* Q2 shows the highest order volume among all quarters

## 🛠 Tools & Technologies

* **Power BI Desktop**
* **Power Query** – Data cleaning & transformation
* **DAX (Data Analysis Expressions)** – Measures & KPIs
* **Data Modeling** – Relationships & schema design

---

## 📐 DAX Measures Used

```DAX
Total Revenue = SUM('Bike Store Sales'[Revenue])

Revenue per Unit = 
DIVIDE(SUM('Bike Store Sales'[Revenue]),
       SUM('Bike Store Sales'[Order_Quantity]))

Avg Order Quantity = 
AVERAGE('Bike Store Sales'[Order_Quantity])

Avg Revenue = 
AVERAGE('Bike Store Sales'[Revenue])
```

---

## 📂 Dashboard Features

* Yearly, Monthly & Quarterly trend analysis
* Product category performance comparison
* Region-wise revenue distribution
* Age group & gender customer segmentation
* Interactive slicers (Country, Month, Product, Quarter)
* Profit vs Cost monitoring

---

## 🖥 Report Pages

### Page 1 – Sales & Customer Analysis

* Orders by Age Group
* Quarterly Orders
* State-wise Costing
* Category Cost Distribution

### Page 2 – Revenue & Performance Analysis

* Monthly Revenue Trends
* Revenue by Category
* Revenue by Region
* Yearly Revenue Growth

---

## ▶️ How to Use

1. Download the `.pbix` file
2. Open in **Power BI Desktop**
3. Use slicers to filter by:

   * Product
   * Region
   * Month
   * Age Group

## 📈 Future Improvements

* Add forecasting using time series analysis
* Create customer retention metrics
* Integrate SQL database connection
* Deploy to Power BI Service

## 👨‍💻 Author

**Atharva Kadu**
Aspiring Data Analyst | Power BI | SQL | Python
