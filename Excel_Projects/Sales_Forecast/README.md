# Sales Forecast Excel Project
## Project Overview

**Project Title**: Sales Forecast  
**Platform Used**: Microsoft Excel  
**Data Source**: Udemy "Build 45 Real-World Power BI Projects for BI & Data Analysts" Course.    
**Analytics Approach**: Descriptive, Scenario-Based (What-if) & Predictive Analytics (Forecast Sheet).

This Excel project integrates descriptive analytics, scenario‑based modeling, and predictive forecasting to provide a complete view of business performance. It summarizes historical trends, simulates the impact of price changes through What‑If analysis, and projects future outcomes using Excel‑based forecasting models.

## Core Skills Applied  

1. Data cleaning.
2. Pivot tables and charts.
3. Interactive slicers.
4. Data Visualization & Dashboard Design.

## Project Structure

### 1. Data Import  
- Connected to the original data source and loaded the financials table into Power Query for transformation.

### 2. Data Cleaning
I applied several pre‑processing steps to ensure data accuracy and consistency, including:  
- Renaming and standardizing column names.
- Applying correct data types (e.g., Date, Text, Whole Number, Decimal Number) to support proper aggregation, calculations, and sorting.
- Removing irrelevant or bad records (such as blank columns, invalid entries, errors, and unhelpful data).
- Adding custom transformation columns (such as Month Number, Month Name, and Year) to enable easier grouping, filtering, PivotTable analysis, and forecasting.
- Replacing inconsistent values by correcting variations in product names, fixing formatting issues, and standardizing country and date formats.
- Validating the dataset using the Column Quality and Column Profile features across all 700 rows.

### 3. Pivot Tables & Charts
After cleaning the dataset, I created multiple Excel PivotTables to summarize and analyze performance metrics such as:  
- Total Net Sales
- Total Profit
- Profit Margin
- Units Sold
- Country vs. Discount Band
- Segment vs. Discount Band
- Product vs. Discount Band
- Profit by Segment
- Units Sold by Country
- Cost of Goods Sold (COGS) vs Net Sales Over Time

This structured pivot model ensured reliable, dynamic reporting throughout the dashboard and the pivot tables served as the data source for the KPI cards, line, bar and column charts.

### 4. Interactive Slicers
To enhance user interactivity, I added slicers for:  
- Timeline: Month & Year
- Product
- Country

These slicers allow users to filter all connected pivot tables and visuals at once, enabling quick insights and ad‑hoc exploration.

### 5. Data Visualization & Dashboard Design

#### a. Descriptive Analysis    
**i. Card Visuals:** Designed card visuals to highlight key metrics, including Total Net Sales, Total Profit, Profit Margin, and Units Sold.   


- Total Net sales was $118.73 M.
- Profit totaled $16.89 M.
- Total units sold over the period reached about 1.13M.
- Profit margin stood at approximately 14.2%

**ii. Column Chart:** Used a Column Chart to showcase the number of units sold per country.  


- Canada recorded the highest number of units sold, totaling 247,429.
- France followed closely with 240,931 units sold.
- The United States ranked next with 232,628 units.
- Mexico recorded 203,325 units sold.
- Germany had the lowest sales volume at 201,494 units.

**iii. Bar Chart:** Used a Bar Chart to compare profit amounts across segments.  


- 



