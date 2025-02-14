# Plants Co. Sales Performance Analysis (Power BI)

## Overview
For this project, I worked on analyzing sales data for Plants Co., a fictitious company, using Power BI. My focus was on cleaning the dataset, designing a well-structured data model, and implementing Year-to-Date (YTD) and Previous Year-to-Date (PYTD) measures to track performance trends. I created various visualizations to explore sales performance across different categories like country, month, and product type.

## Data Cleaning & Preparation
To ensure accurate analysis, I started by:
- Renaming columns for consistency and clarity.
- Removing duplicates in primary keys and duplicate orders.
- Checking for data integrity before moving on to modeling.

## Data Modeling
I created a date dimension table and then structured the data using a star schema, making it efficient for querying and analysis. The model consists of a central fact table (Sales) connected to multiple dimension tables 

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
- **Bottom 10 YTD vs PYTD by Country**: Highlights the worst-performing countries.
- **YTD vs PYTD by Month, Country, and Product**: A waterfall chart illustrating performance trends.
- **Gross Profit YTD & PYTD by Month**: A stacked bar + line chart breaking down profits by product type.
- **Account Profitability Segmentation**: A scatter plot visualizing profit distribution with dynamic reference lines.


**Tools Used:** Power BI, DAX, Power Query
