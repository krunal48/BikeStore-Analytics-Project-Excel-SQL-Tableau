# BikeStore Analytics Project 🚴‍♂️📊

## Overview
The **BikeStore Analytics Project** is a comprehensive case study that demonstrates the integration of multiple data tables into a unified dataset using SQL, followed by analysis and visualization with Excel and Tableau. The project showcases advanced skills in data manipulation, transformation, and visualization to generate actionable business insights.

---

## Project Objectives
1. **Data Integration**: Join multiple tables from the BikeStore database to create a consolidated dataset.
2. **Data Analysis**: Extract and analyze key trends using SQL and Excel.
3. **Data Visualization**: Build interactive dashboards in Excel and Tableau for business decision-making.

---

## Tools and Technologies
- **SQL**: For joining and transforming data from multiple tables.
- **Excel**: For pivot tables, charts, and dashboard creation.
- **Tableau**: For advanced data visualization and storytelling.

---

## Dataset Description
### Source Tables (SQL)
The original data resides in multiple tables (provided in the SQL Server database), including:
- **Orders**
- **Customers**
- **Products**
- **Categories**
- **Brands**
- **Stores**
- **Sales Representatives**

### Final Dataset (Consolidated Table)
After integrating the tables using SQL, the final dataset contains the following fields:
- **order_id**: Unique identifier for each order.
- **customers**: Customer names or IDs.
- **city**: City where the purchase occurred.
- **state**: State where the purchase occurred.
- **order_date**: Date of the order.
- **total_units**: Total units sold in an order.
- **revenue**: Total revenue generated from the order.
- **product_name**: Name of the product sold.
- **category_name**: Product category (e.g., bikes, accessories).
- **brand_name**: Brand of the product.
- **store_name**: Store where the purchase was made.
- **sales_rep**: Sales representative responsible for the order.

---

## Key Insights and Results
### SQL Analysis
- **Data Integration**: Successfully joined multiple tables into a unified dataset using SQL.
- **Top Performing Products**: Identified products generating the most revenue.
- **Customer Segmentation**: Grouped customers based on purchasing patterns and revenue contributions.
- **Regional Analysis**: Analyzed revenue contributions by city and state.

### Excel Dashboard
- **Pivot Analysis**: Highlighted trends in product categories, brands, and sales representatives.
- **Interactive Features**: Added slicers for dynamic filtering by store, sales rep, and product.
- **Geographical Insights**: Visualized state-wise revenue using map charts.

### Tableau Visualizations
- **Executive Summary Dashboard**: Combined key metrics, including revenue trends, top products, and customer analysis.
- **Interactive Features**: Enabled drill-downs using action filters and parameters.
- **Advanced Visuals**: Created Top N charts and contextual calculated fields for insightful reporting.

---

## Project Workflow
### SQL Section
1. **Database Exploration**: Understand the schema and relationships between tables.
2. **Data Integration**: Write SQL queries to join all relevant tables.
3. **Export Final Dataset**: Save the consolidated data as a CSV or Excel file for further analysis.

### Excel Section
1. **Import Final Dataset**: Load the SQL-generated dataset into Excel.
2. **Pivot Table Analysis**: Analyze revenue trends, category performance, and customer behavior.
3. **Dashboard Creation**: Build an interactive dashboard with slicers and charts.

### Tableau Section
1. **Connect Dataset**: Import the final dataset from Excel into Tableau.
2. **Data Visualizations**: Create engaging visuals like Top N charts, line graphs, and maps.
3. **Executive Dashboard**: Develop an interactive dashboard for stakeholders.
