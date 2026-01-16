# Sales Analysis (Power BI)

**Author:** Su Wai  
**Tool:** Microsoft Power BI Desktop

## Overview
An interactive Power BI report analyzing sales performance across time, products, customers, and regions. It provides insights into **Revenue**, **Profit**, **Average Order Value (AOV)**, **YoY/MoM trends**, and **Top performers**.

## Preview
<img width="1136" height="643" alt="Screenshot 2025-08-13 224858" src="https://github.com/user-attachments/assets/60334678-b275-42c7-9c73-aff685d1b032" />

## Open the Report
- File: `Sales_Analysis_PowerBI.pbix`
- Alternative: use the `.pbit` template for smaller file size without embedded data.

## Data Setup
If your report uses parameters, update them after opening:
- `DataFolderPath` → location of your sample data
- `ServerName`, `DatabaseName` (if using SQL)
- Credentials are **not** included.

## Model & Logic
- **Star schema**: FactSales, DimDate, DimProduct, DimCustomer, DimRegion.
- **DAX measures**: (export to `dax/measures.dax`)
- **Power Query (M)**: (export to `queries/power_query/`)

## Refresh
1. Open in Power BI Desktop  
2. Update parameters and data paths  
3. Click **Refresh**

## Project Structure
