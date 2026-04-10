# File 7: Data Analytics & Business Intelligence
## Task 2: Data Integration from Multiple Sources (Excel + SQL)

### 1. Project Overview
This project demonstrates the integration of data from two distinct sources to create a unified business report. 
- **Source A (Excel):** Contains Transactional Sales Data (Order Date, Product ID, Quantity, Price).
- **Source B (SQL Server):** Contains Master Customer Data (Customer ID, Segment, Region, Demographics).

### 2. ETL Process (Power Query)
To unify the data, the following transformations were performed in Power Query:
- **Data Cleaning:** Removed null values from the 'CustomerID' column and standardized date formats.
- **Merging:** Performed a **Left Outer Join** between the Sales table and Customer table using `CustomerID` as the primary key.
- **Data Modeling:** Created a **One-to-Many relationship** in the Model View to ensure referential integrity.

### 3. Key Insights Delivered
- **Segmented Sales:** Analyzed which customer segment (Corporate vs. Home Office) contributes most to the revenue.
- **Regional Heatmap:** Integrated SQL location data with Excel sales figures to plot geographic performance.
- **Unified KPIs:** Real-time calculation of Total Revenue and Average Order Value across both data sources.

### 4. How to View
1. Download the `Sales_Unified_Report.pbix` file.
2. Open with Power BI Desktop.
3. Refresh data to see live connections (requires SQL Server access).
