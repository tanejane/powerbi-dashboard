# powerbi-dashboard
# 📌 Project Overview
This Business Intelligence (BI) project was developed for Velocity Cycles, a global bicycle manufacturer preparing for expansion into North America, Europe, and Asia-Pacific. The project applies BI techniques to address key challenges such as:
-Lack of real-time sales and trend tracking
-Limited insights into customer preferences
-Need for effective regional and customer segmentation
The solution uses Microsoft’s BI stack (SQL Server, SSAS, and Power BI) to extract, model, and visualize enterprise data for strategic decision-making

# 📊 BI Solution Architecture
🔗 Data Source:
Connected to the VelocityCyclesDW SQL Server database using Visual Studio’s Data Source Wizard.

# 🔍 Data Source View (DSV):
Included key fact tables (FactInternetSales, FactResellerSales) and dimension tables (DimProduct, DimCustomer, DimDate, DimPromotion, DimSalesTerritory, etc.), enabling relationships and hierarchies for OLAP analysis.

# 🧊 Cube Structure:
Measures such as SalesAmount, OrderQuantity, and Gross Profit were included in the cube, with time, product, and geography hierarchies to support multidimensional slicing and drill-down.

# 📈 Power BI Dashboard:
1. Sales Performance Dashboard
A dynamic dashboard to evaluate sales trends across time, regions, products, resellers, and promotions.
![image](https://github.com/user-attachments/assets/4a1f242e-1619-4dac-89e2-26944add9a72)

Key Features:
🔘 Year Slicer – Filter entire dashboard by selected year(s)
💵 Total Sales Card – Summarizes all sales revenue (~$109.81M)
📉 Line Chart – Monthly sales trends (e.g., peaks in December)
🌍 Pie Chart – Sales by country (e.g., Australia, UK, Germany)
🛒 Table – Best-selling products (e.g., Mountain-200 Black, 46)
🏬 Bar Chart – Top reseller contributions
🧃 Donut Chart – Promotion effectiveness by sales
🚲 Column Chart – Sales by product category (e.g., Bikes ~ $95M)

2. Profitability Dashboard
A financial dashboard analyzing gross profit, product cost, and promotional impacts.
![image](https://github.com/user-attachments/assets/a304a535-c74a-49ef-bdc8-ad7d42c231d2)

Key Features:
📅 Year Slicer – Filter across 2020–2024
📈 Line Chart – Forecasted gross profit (2025–2029) with trend analysis
📊 Bar Chart – Gross profit year-over-year with color indicators
🟪 Clustered Column Chart – Compare sales vs. cost across channels
💰 Gross Profit Card – Total gross profit (~$12.55M)
🧾 Table – Gross profit by promotion (e.g., “No Discount” = most profitable)
🥧 Pie Chart – Profit by product subcategory (e.g., Mountain Bikes = $5.93M)

3. Customer Insights Dashboard
Analyzes customer behavior, demographics, and geographic distribution to support marketing and retention.
![image](https://github.com/user-attachments/assets/5f2e5bef-c531-46ad-8031-23e8105d3fed)

Key Features:
📅 Year Slicer – Time-based customer insights
👥 Total Customers Card – Total unique customers (~18.48K)
♀️♂️ Gender Pie Chart – Nearly equal gender split
📋 Sales Table – Internet sales per customer
🗺️ Map – Customer count by region (e.g., high in North America & Australia)
📈 Customer Growth Line Chart – Notable spike in 2023
📦 Clustered Bar Chart – Order quantity vs. frequency per customer
📊 Age Distribution Chart – Most customers aged 40–60

# ✅ Tools Used
SQL Server Management Studio (SSMS)
SQL Server Data Tools (SSDT) in Visual Studio (SSAS OLAP)
Multidimensional Expressions (MDX)
Power BI (for final visualization and dashboarding)

