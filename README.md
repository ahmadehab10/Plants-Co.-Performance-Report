# Plants Co. Sales Performance Analysis (Power BI)

## Overview
This project analyzes sales data for **Plants Co.**, a fictitious company, using **Power BI**. The primary focus is on **data cleaning, star schema modeling, and implementing Year-to-Date (YTD) and Previous Year-to-Date (PYTD) measures** to evaluate performance trends. Various visualizations help understand business performance across different dimensions such as **country, month, and product type**.

## Data Cleaning & Preparation
- Renamed columns for consistency and clarity.
- Removed duplicates in primary keys and duplicate orders.
- Ensured data integrity before proceeding to modeling.

## Data Modeling
A **star schema** was implemented to optimize performance and enhance analytical capabilities. The data model consists of a **fact table** (Sales) and multiple **dimension tables** (Date, Products, Customers, etc.).

## Key DAX Measures
The project focuses on **performance measures** for analyzing sales trends.

### Sales & Profit Measures
- **Total Sales**
- **Total Quantity**
- **Gross Profit**

### Time Intelligence Measures
- **Year-to-Date (YTD) Sales**
- **Previous Year-to-Date (PYTD) Sales**
- **Switch Measures for Dynamic Selection**

These measures allow users to dynamically toggle between different performance metrics.

## Visualizations & Insights
To enhance decision-making, **interactive visualizations** were created, including:

- **Performance by Country**
- **Sales & Profit Over Time**
- **Product Type Analysis**
- **Comparison of YTD vs. PYTD**

## Conclusion
This Power BI project demonstrates a structured approach to **data cleaning, modeling, and visualization**. By leveraging **DAX time intelligence functions**, key business insights were extracted, providing valuable analytics for decision-making.

## How to Use
1. **Download** the Power BI file (`.pbix`).
2. Ensure that all necessary tables are included in the **data model**.
3. **Int
