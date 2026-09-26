# Assignment 4 – Data Modelling

## Overview

This assignment focused on building and enhancing a Power BI data model using the AdventureWorks dataset. The project involved creating relationships between tables, adding calculated columns, and preparing the model for analysis.

## Data Modelling

The following tables were used in the Power BI data model:

- DimCurrency
- DimCustomer
- DimDate
- DimProduct
- DimProductCategory
- DimProductSubcategory
- DimPromotion
- DimSalesTerritory
- FactInternetSales

Relationships were created and configured between the relevant dimension and fact tables, including date, product, and product-category relationships.

## Calculated Columns

The following calculated columns were created as part of the assignment:

### DimCustomer
- `IncomeStatus`
- `DaysSinceFirstPurchase`
- `FullName`
- `MaleFemale`
- `Relationship`

### DimProductSubcategory
- `MainCategory`

### DimPromotion
- `PromotionLengthDays`

### FactInternetSales
- `Profit`

These calculated columns were created to classify customer information, derive purchase-related information, establish product categories, calculate promotion duration, and determine profit.

## Tools & Technologies

- Power BI Desktop
- DAX
- Microsoft Excel
- AdventureWorks

## Files

- `Adventure Works Data Modelling.pbix` – Power BI file containing the completed data model and calculated columns.
- `Data_Model_Relationships.png` – Screenshot of the Power BI data model and table relationships.
- `Calculated_Columns_DimCustomer.png` – Screenshot showing calculated columns created in the DimCustomer table.

## Learning Outcome

This assignment provided practical experience in designing a Power BI data model, creating relationships between tables, and using DAX calculated columns to derive and transform analytical fields.

## Note

This project was completed as part of my Power BI Certification Training.
