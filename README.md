# Plant Co. Performance Report

## Overview

This report provides a detailed analysis of **Plant Co.**'s performance, focusing on sales, product quantities, cost of goods sold (COGS), and profitability. The updated report now incorporates new table structures and added columns to provide deeper insights. Key metrics such as **YTD (Year-to-Date)**, **PTD (Period-to-Date)**, and **GP% (Gross Profit Percentage)** are visualized for comparison across regions, products, and timelines.

## Data Sources

### 1. **Fact_Sales** (Updated)
The **Fact_Sales** table includes detailed transaction data, now with additional columns to better segment the sales data:
- **Product_id**: Unique identifier for each product.
- **Sales_USD**: Total sales in USD for the product.
- **Quantity**: Quantity of the product sold.
- **Price_USD**: Price per unit in USD.
- **COGS_USD**: Cost of Goods Sold in USD.
- **Date_Time**: The date and time of the transaction.
- **Account_id**: Identifier for the account associated with the transaction.

### 2. **Dim_Account**
The **Dim_Account** table provides detailed information about accounts involved in sales transactions. It includes columns like:
- **Country_code**: The country code where the account is located.
- **Account**: Name of the account (company).
- **Account_id**: Unique identifier for the account.
- **Latitude2** and **Longitude**: Geographical coordinates of the account's location.

### 3. **Dim_Product**
The **Dim_Product** table is designed to provide detailed information about products, including the new columns added for better categorization:
- **Product_Family**: The family of the product (e.g., Cucurbitaceae, Platanaceae).
- **Product_Group**: Specific group within the product family.
- **Product_Name**: Name of the product.
- **Product_Size**: The size of the product (e.g., Small, Medium, Large).
- **Product_Type**: The type of product (e.g., Landscape, Outdoor).

### 4. **Dim_Date**
The **Dim_Date** table helps segment the data based on time, with columns for year, month, and day, allowing for detailed time-series analysis.

## Key Insights

- **Sales Performance**: The report identifies key products based on sales performance, highlighting the highest-grossing products and their associated quantities sold.
- **Cost and Profitability**: By comparing **COGS_USD** to **Sales_USD**, the report provides insight into the profitability of each product and the overall business.
- **Geographic Insights**: The **Dim_Account** table allows for geographic performance analysis by region, showcasing sales trends by country or region.
- **Product Trends**: The updated **Dim_Product** table helps categorize and track product performance across various groups and families.

### Example Visual:
Below is a visual extracted from the Power BI report, showcasing the **Quantity Performance** for 2023, including key metrics like **YTD**, **PTD**, and **GP%**, and comparing product types and country-wise performance.

![Visualization](https://github.com/user-attachments/assets/dff9a03d-eb34-499b-8234-5ffa7f8356fe)


## Conclusion

This updated report, with new tables and columns, provides deeper insights into **Plant Co.**'s business performance. By analyzing sales, costs, products, and geographic regions, it helps identify opportunities for growth, efficiency improvements, and better decision-making in sales strategy and inventory management.

---