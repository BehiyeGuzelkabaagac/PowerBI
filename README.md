# 📊 Global Superstore Sales Analytics - Power BI Project 1  

🚀 This project analyzes sales data from the **Global Superstore Dataset** using Power BI, focusing on data modeling, DAX calculations, and interactive visualizations to derive business insights.  

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

- # 📊 Advanced Power BI Dashboard – Global Superstore Project 2

This project showcases a comprehensive and interactive Business Intelligence dashboard created using Power BI and the **Global Superstore Dataset**.

---

## 🚀 Project Objectives

The main goal was to design a **user-friendly, visually engaging, and decision-supportive dashboard** with enhanced interactivity. Key focus areas included:

- RFM Analysis (Recency, Frequency, Monetary)
- Regional performance comparison
- Product category insights
- Time-based sales and profit trends
- Discount and return analysis
- Shipping metrics and delivery performance
- Customer segmentation and behavior analysis
- Role-based data security (Row-Level Security)

---

## 🛠️ Dashboard Structure

1. **Overall Performance Page**
   - KPI Cards (Sales, Profit, Customers, etc.)
   - Sales Trend by Order Date
   - Slicers for Year, Region, Market, Country

2. **Market Sales Trend**
   - Yearly and Quarterly Sales Trends
   - Segment and Market Comparison

3. **Profit Analysis**
   - Category/Sub-Category/Segment level views
   - Bookmarks for Loss vs. Net Profit

4. **Discount Analysis**
   - Impact of discounts on profitability

5. **Regional Analysis**
   - Sales by Country (Top/Bottom 5)
   - Market distribution with donut charts and maps

6. **Category Analysis**
   - Hierarchical breakdown: Segment > Category > Sub-Category
   - Bookmarks for Profit vs. Sales focus

7. **Return Analysis**
   - Top returned items and customers
   - Funnel chart and Return Rate trend

8. **Shipping Analysis**
   - Delivery times, Shipping costs
   - Charts based on Ship Mode and Order Priority

9. **RFM Analysis**
   - Segmenting customers by RFM scores
   - Exportable tables, interactive treemaps, and bookmarks for:
     - Best Customers
     - Customers at Risk
     - Champions of Corporate

10. **Main Navigation Page**
    - Navigation buttons to all sections
    - Back buttons and slicer reset

11. **Row-Level Security (RLS)**
    - Region-based, Country-based, and Segment-based role restrictions

---

## 📁 Dataset

- [Global Superstore 2016 Dataset on Kaggle](https://www.kaggle.com/datasets/jamsbrown/global-superstore-data-of-2016/data)

---

## 🚀 **How to Use**  
1. Download the `Project1_BI.pbix` file.  
2. Open in Power BI Desktop (ensure you have the latest version).  
3. Connect to your data source or use the provided sample dataset.  
4. Explore filters and hover interactions for deeper insights.

## 📬 Contact Me
💡 Feel free to share your thoughts or contribute to this project!
- 📧 Email: behiyegka@gmail.com
- 💼[Linkedin](https://www.linkedin.com/in/behiye-guzelkabaagac/)
- 🐙 [GitHub](https://github.com/BehiyeGuzelkabaagac)
 
 
