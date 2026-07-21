# Dream Craft Sales Analytics Dashboard

## Overview

This project demonstrates the development of an end-to-end Business Intelligence solution using **Snowflake** and **Power BI** for Dream Craft, a company specializing in classic car models and collectibles.

The project covers database design, SQL development, data transformation, and interactive dashboard creation. Sales data was centralized in Snowflake, connected to Power BI, and transformed into interactive reports that provide insights into revenue, customer distribution, product performance, and shipment status.

The solution enables business users to monitor key performance indicators (KPIs), identify top customers and products, analyze monthly sales trends, and explore customer and shipment insights through dynamic visualizations.


## Tools & Technologies

- Power BI
- Snowflake
- SnowSQL
- SQL
- Power Query
- DAX

---

## Project Workflow

### Database Development (Snowflake)

- Created the DreamCraft database and schema
- Designed the relational database based on the ER diagram
- Created all required tables
- Inserted records into each table
- Handled missing values using SQL
- Created calculated columns:
  - Markup Percentage
  - Total Cost
- Created SQL Views:
  - Sale_Details
  - High_Value_Customers
- Developed Stored Procedures:
  - GET_MARKUP_HIGHER
  - GET_HIGHCREDIT_CUSTOMER
- Loaded and unloaded data using Snowflake
- Retrieved deleted data using OFFSET and UNDROP

---

### Data Preparation

- Connected Snowflake with Power BI
- Imported the required tables
- Removed unnecessary columns containing excessive null values
- Built relationships between all tables
- Created DAX measures for business KPIs

---

## Report 1 – Sales Performance Overview

The first report focuses on overall sales performance.

### Visuals Included

- Revenue Card
- Average Markup Percentage Gauge
- Customer Distribution by Country (Treemap)
- Top 10 Customers
- Revenue by Month
- Year Slicer

---

## Report 2 – Sales & Customer Insights

The second report focuses on customer behavior and product performance.

### Visuals Included

- Revenue Card
- Customer Count
- Order Count
- Top Selling Product Line
- Product Sold in Quantity
- Yearly Customer Order Count
- Overall Shipment Status
- Year Slicer

---

## Key Features

- Interactive filtering using slicers
- KPI Cards
- Gauge Chart
- Treemap
- Bar Charts
- Column Charts
- Pie Chart
  
- Donut Chart
- Cross-filtering between visuals
