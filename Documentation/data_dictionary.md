# Data Dictionary

## FactInternetSales

Contains transactional sales information.

| Column | Description |
|---|---|
| ProductKey | Unique identifier for the product |
| CustomerKey | Unique identifier for the customer |
| OrderDate | Date of the sales order |
| OrderQuantity | Quantity of products sold |
| UnitPrice | Selling price per unit |
| TotalSales | Total sales/revenue amount |
| TotalCost | Total cost of the products |
| TotalProfit | Revenue minus cost |

## DimProduct

Contains product information.

| Column | Description |
|---|---|
| ProductKey | Unique product identifier |
| ProductName | Name of the product |
| ProductCategory | Product category |
| ProductSubcategory | Product subcategory |
| StandardCost | Standard cost of the product |

## DimCustomer

Contains customer information.

| Column | Description |
|---|---|
| CustomerKey | Unique customer identifier |
| FirstName | Customer first name |
| LastName | Customer last name |
| FullName | Combined customer name |

## DimGeography

Contains geographical information.

## DimSalesTerritory

Contains sales territory information.

## DimDate

Contains calendar and date-related information used for time-based analysis.