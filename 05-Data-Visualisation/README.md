# Assignment 5 – Data Visualization

## Overview

This assignment focused on building an interactive Power BI report using the AdventureWorksLT dataset. The project covered data preparation, data modeling, calculated columns and measures, filtering, and the creation of interactive visualizations.

## Data Preparation

The following tasks were performed:

- Connected Power BI to the AdventureWorksLT database.
- Loaded customer and sales-related data.
- Renamed and cleaned tables and columns.
- Created a `FullAddress` column by combining address-related fields.
- Created a `LineTotal` column using Order Quantity and List Price.
- Created a `TargetSales` measure by increasing LineTotal by 2%.
- Imported state data and combined it with the sales data.
- Applied appropriate data categories to location-related fields.
- Hid selected technical/ID columns from the Report view.

## Report Pages

### Page 1 – Sales Analysis

The first report page contains sales-focused visualizations:

- **Target Sales** – Gauge comparing LineTotal with the TargetSales measure.
- **Top Selling Companies** – Pie chart showing sales by company.
- **Sales by Main Category** – Stacked bar chart for sales/order quantity by main category.
- **Sales by Main Category** – Donut chart showing sales distribution across categories.
- **Top Selling Bikes** – Column chart filtered to display bikes meeting the specified sales threshold.

### Page 2 – Geographic Sales Analysis

The second report page focuses on geographical sales analysis:

- **World Sales by City** – Map showing sales by city.
- **Sales by State** – Map showing sales by state.

## Tools & Technologies

- Power BI Desktop
- Power Query
- AdventureWorksLT
- Microsoft SQL Server

## Files

- `AdventureWorksLT_Sales_5.pbix` – Completed Power BI report containing both report pages.
- `Sales_Analysis.png` – Screenshot of the Sales Analysis page.
- `Geographic_Sales_Analysis.png` – Screenshot of the Geographic Sales Analysis page.

## Learning Outcome

This assignment provided practical experience in preparing and modeling data in Power BI, creating calculated columns and measures, applying filters, and developing interactive sales and geographic visualizations.

## Note

This project was completed as part of my Power BI Certification Training.
