# Assignment 3 – Shaping and Combining Data

## Overview

This assignment focused on importing, shaping, transforming, and combining sales data from different regional sources using Power BI and Power Query.

## Data Preparation

The project involved working with sales data for:

- Europe
- North America

The data was transformed and standardized before being combined for analysis.

## Data Shaping & Transformation

The following Power Query transformations were performed:

- Imported the Europe and North America sales data.
- Removed unnecessary columns such as ProductKey and SalesOrderNumber.
- Renamed columns for better readability and consistency.
- Renamed fields such as:
  - SalesTerritoryCountry → Country
  - SalesTerritoryGroup → Sales Territory
  - EnglishProductCategoryName → Main Category
  - EnglishProductSubcategoryName → Sub Category
  - EnglishProductName → Product
- Reordered columns, including moving the Color column.
- Applied the same transformations to the North America data.
- Appended the Europe and North America tables into a combined dataset.

## Data Integration

A separate Country Codes dataset was imported and merged with the combined sales data.

The country code information was extracted from the merged data and added as:

- Country Code

This provided standardized country identifiers for the sales data.

## Data Model

The final Power BI model contains:

- Europe
- North America
- Europe and North America
- Country Codes

Relationships were created between the combined sales data and the Country Codes table.

## Tools & Technologies

- Power BI Desktop
- Power Query
- Microsoft Excel

## Files

- `Shaping and Combining Data.pbix` – Power BI file containing the completed transformations and data model.
- `Data_Model_Relationships.png` – Screenshot of the Power BI data model.
- `Country_Codes.png` – Screenshot showing the Country Codes table.

## Learning Outcome

This assignment provided practical experience in Power Query data transformation, column standardization, appending datasets, merging queries, and creating relationships between datasets.

## Note

This project was completed as part of my Power BI Certification Training.
