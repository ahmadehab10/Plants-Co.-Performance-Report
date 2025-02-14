# Plants Co. Sales Performance Analysis (Power BI)

## Overview
For this project, I worked on analyzing sales data for Plants Co., a fictitious company, using Power BI. My focus was on cleaning the dataset, designing a well-structured data model, and implementing Year-to-Date (YTD) and Previous Year-to-Date (PYTD) measures to track performance trends. I created various visualizations to explore sales performance across different categories like country, month, and product type.

## Data Cleaning & Preparation
To ensure accurate analysis, I started by:
- Renaming columns for consistency and clarity.
- Removing duplicates in primary keys and duplicate orders.
- Checking for data integrity before moving on to modeling.

## Data Modeling
I structured the data using a star schema, making it efficient for querying and analysis. The model consists of a central fact table (Sales) connected to multiple dimension tables (Date, Products, Customers, etc.).

## Key DAX Measures
To gain insights into business performance, I created several key measures:

### Sales & Profit Measures
- **Total Sales**
- **Total Quantity**
- **Gross Profit**

### Time Intelligence Measures
- **Year-to-Date (YTD) Sales**
- **Previous Year-to-Date (PYTD) Sales**
- **Switch Measures for Dynamic Selection**

These allow easy comparisons between current and past performance, with dynamic filters for more flexibility.

## Visualizations & Insights
To bring the data to life, I designed interactive visualizations, including:
- **Sales Performance by Country**
- **Sales & Profit Trends Over Time**
- **Product Type Analysis**
- **YTD vs. PYTD Comparisons**

These visualizations help identify key trends and areas for improvement in sales.

## Conclusion
This project was a great way to apply data cleaning, modeling, and DAX time intelligence functions in Power BI. The final dashboard provides valuable insights into business performance, making it easier to track trends and make informed decisions.

## How to Use
1. **Download** the Power BI file (.pbix).
2. Ensure all necessary tables are properly connected in the **data model**.
3. **Use slicers** to filter and explore different views.
4. **Analyze YTD and PYTD metrics** to compare sales performance across various dimensions.

---

**Author:** [Your Name]  
**Tools Used:** Power BI, DAX, SQL, Data Modeling
