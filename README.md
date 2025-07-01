# 📊 Global Superstore Sales Analytics - Power BI Project 1  

This project analyzes sales data from the **Global Superstore Dataset** using Power BI, focusing on data modeling, DAX calculations, and interactive visualizations to derive business insights.  

## 🔍 **Project Overview**  
- **Objective**: Transform raw sales data into a structured data warehouse model and create an interactive dashboard for performance tracking.  
- **Dataset**: Global Superstore (includes orders, customers, products, and regional data).  
- **Tools Used**: Power BI, Power Query, DAX.  

## 🛠 **Key Features**  

### **1. Data Modeling & Normalization**  
- Designed a **Star Schema** with fact and dimension tables (`FactSales`, `DimCustomer`, `DimProduct`, etc.).  
- Created an **ER Diagram** to visualize relationships.  
- Implemented **incremental refresh** to optimize data loading (updates only the most recent year).  

### **2. DAX Calculations**  
- **Calculated Columns**:  
  - `Prep Days` (days between order and shipment).  
  - `Profitability Category` (Profit, Loss, Break-even).  
- **Measures**:  
  - Time-intelligent metrics: `Sales YTD`, `Sales QTD`, `Sales LY`.  
  - Financial KPIs: `Total Sales`, `Average Profit`, `Return Rate`.  
- **Calculated Tables**:  
  - `Segment Sales Summary` (aggregated metrics by customer segment).  
  - Separate `Date Tables` for `Order Date` and `Ship Date`.  

### **3. Interactive Dashboard**  
- **KPIs**: Total Sales, Profit, Orders, Customers.  
- **Visualizations**:  
  - Market-wise sales (Bar chart).  
  - Category-wise sales (Donut chart).  
  - Quarterly sales trends with YoY comparison (Line chart).  
- **Filters**: Country, State, City.    

## 🚀 **How to Use**  
1. Download the `GlobalSuperstore.pbix` file.  
2. Open in Power BI Desktop (ensure you have the latest version).  
3. Connect to your data source or use the provided sample dataset.  
4. Explore filters and hover interactions for deeper insights.  
 
 
