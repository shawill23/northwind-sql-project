## Northwind Sales Analysis Dashboard (Power BI + SQL)

## About the Project
This project analyzes the northwind traders dataset to uncover insights on global sales performance, product trends, and regional revenue distribution. The dashboard is designed to demonstate end-to-end data analytics skills - from SQL querying and data modeling to Power BI visualization and storytelling. 

## Overview 
The Northwind Sales Dashboard is an interactive Power BI report that visualizes global sales performance using data from the Northwind Traders Database. 
Its designed to showcase essential analytics skills - data modeling, DAX calculations, and storytelling through clean visuals.

## Key features 
- **Sales Overview Page -** Displays total revenue and performance by product category.
- **Product Performance Page -** Highlights the top 10 best-selling products with total revenue.
- **Regional Performance Page -** Interactive filled-map visualization showing sales by country and category.

## Tools & Techniques 
- **Power BI Desktop** (data modeling + visual desgin)
- **SQL Server / Northwind database** (data source)
- **DAX functions** (Star schema connecting Orders, Order details, Products, Categories)

## Skills Demonstrated 
- Data extraction and transformation (SQL queries)
- Relationship modeling and normalization
- Creating calculated columns and measures with DAX
- Designing professional dashboards for business presentation
  
## KPIs 
- **Total Revenue** - $1.35 M
- **Top Products** - Cote de Blaye, Thuringer Rostbratwurst, Raclette Courdavault
- **Regions with Highest Sales** - Europe and North America

## Visuals Included 
- KPI card (for global revenue)
- Bar chart (Top 10 products by revenue)
- Line Chart (Total sales trend by year)
- Map visual (Sales by region and category)
- Slciers (for date and category filtering)

## Data Model Summary 
- **northwind_orders** (cntains OrderDate, CustomerID, ShipCountry)
- **northwind_order_details** (links OrderID <-> OrderID, includes UnitPrice and Quantity)
- **northwind_products** (connects via ProductID to Categories)
- **northwind_categories** (provides CategoryName used in slicers and maps)

## Learning Outcomes 
- Build a fully interactive Power BI dashboard from scratch.
- Practiced dara relationships and model desgin for real datasets.
- Created clean, story-driven visualizations for stakeholders.

## How to use 
1. Clone this repository
2. Open the .pbix file in Power BO Desktop
3. Refresh the connection to your local SQL Server database
4. Interact with filters and visuals

## Author 
Shakira Williams | Norfolk, Va
Google Data Analytics | Microsoft Power BI Certified
Aspiring Data Analyst | Skilled in SQL, Power BI, and Data Visualization 


