# Sales_Customer_Dashboard_Tableau
Tableau Dashboard for analyzing Sales and Customer performance using a star schema model and key business KPIs

<p align="center">
  <img src="https://img.shields.io/badge/Tableau-yellow?style=for-the-badge" alt="Power BI">
  <img src="https://img.shields.io/badge/Dashboard-blue?style=for-the-badge" alt="Dashboard">
  <img src="https://img.shields.io/badge/Data_Source-Excel-217346?style=for-the-badge" alt="Data Source">
</p>


# 📑Table of Contents

- [Overview](#overview)
- [Project Objectives](#project-objectives)
- [Dashboard Metrics](#dashboard-metrics)
- [Technology Stack](#technology-stack)
- [How to View](#how-to-view)
- [Future Enhancements](#future-enhancements)
- [Author](#author)

## 📊 Dashboard Preview
<img width="1197" height="814" alt="Dashboard" src="https://github.com/user-attachments/assets/d537a8bb-c3ba-488e-91fb-241344be1c77" />


## 🎯 Project Objectives

- **Track Key KPIs:** Monitor essential business indicators including **Total Sales**, **Total Profit**, and **Profit Margin (%)**, and their growth compared to the **Previous Year** growth rates.

- **Analyze Trends:** Visualize monthly and yearly **sales and profit trends** to identify performance patterns, seasonal fluctuations, and growth opportunities while detecting potential declines in profitability.

- **Segment Performance:** Break down performance metrics by **Region**, **Product Category**, and **Customer Segment** to pinpoint high-performing markets and products that drive overall profitability.

- **Evaluate Customer Performance:** Identify and highlight the **Top 10 Customers** by profit contribution and sales volume to strengthen key client relationships and focus retention efforts.

- **Monitor Operational Metrics:** Track **Total Number of Orders** and **Unique Customers** to measure business engagement levels, customer retention rates, and overall transaction volume.
- 
## 📊 Dashboard Metrics

### **Performance Indicators**

| Metric | Description | Formula |
|--------|-------------|---------|
| **Total Sales** | Total revenue generated from all completed orders | `SUM(Sales)` |
| **Total Profit** | Net earnings after subtracting product and operational costs | `SUM(Profit)` |
| **Profit Margin (%)** | Percentage of profit earned from total sales, showing overall profitability | `(SUM(Profit) / SUM(Sales)) * 100` |
| **Sales Growth (YoY/MoM)** | Evolution of sales performance comparing current vs. previous periods | `(Current Period - Previous Period) / Previous Period` |
| **Total Customers** | Number of unique customers who made at least one purchase | `COUNTD(CustomerID)` |
| **Total Orders** | Total number of transactions or orders recorded | `COUNT(OrderID)` |
| **Top 10 Customers** | Most profitable customers based on total profit generated | `RANK(SUM(Profit))` |
| **Average Sales per Customer** | Average sales value per customer, highlighting spending behavior | `SUM(Sales) / COUNTD(CustomerID)` |


## 🛠️ Technology Stack

| **Component**                       | **Technology**                                              |
| ----------------------------------- | ----------------------------------------------------------- |
| **Visualization Platform**          | Tableau Public                                              |
| **Data Source**                     | Excel (.csv)                                                |
| **Data Transformation**             | Power Query & Tableau Data Interpreter                      |
| **Data Modeling**                   | Star Schema Model + Calculated Fields in Tableau            |
| **KPI Calculation**                 | DAX-style expressions using Tableau Calculated Fields       |
| **Data Cleaning**                   | Excel / Power Query (null handling, duplicates, formatting) |



## 🚀 How to View

### **Interactive Dashboard**

Experience the full interactivity of the **Sales & Customer Dashboards** directly on Tableau Public:

➡️ **[View Live Dashboard on Tableau Public](https://public.tableau.com/app/profile/habib.aidara/viz/SalesCustomerDashboards_17615605607430/SalesDashboard?publish=yes)**

Both dashboards are available within the same Tableau workbook — simply **click the icons at the top right** to switch between views:

* 🏛️ **Sales Dashboard** → Provides insights into *Sales, Profit, and Quantity trends*
* ⭐ **Customer Dashboard** → Focuses on *Customer performance, orders, and sales distribution*

<img width="160" height="67" alt="image" src="https://github.com/user-attachments/assets/72229582-34ff-44a6-992d-cee06028ea0a" />


---

### **Dashboard Features**

**🔹 Interactive Navigation:**
Click the **Sales icon** 🏛️ to explore the Sales Dashboard, or the **Customer icon** ⭐ to switch to the Customer Dashboard.

**🔹 Interactive Filters:**
Filter by **Region**, **Product Category**, **Customer Segment**, or **Date Range** to dynamically update all metrics and visuals.

**🔹 Cross-filtering:**
Click on bars, lines, or customer names to filter related data across all charts automatically.

**🔹 Drill-down & Highlighting:**
Explore data at multiple levels — from *total sales* to *specific customers or products* — with a single click.

**🔹 Export Options:**
Download KPI summaries or visuals for use in **presentations and reports**.

**🔹 Responsive Layout:**
Optimized for **desktop and browser** view for smooth user experience.

