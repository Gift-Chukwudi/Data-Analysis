# Expense Analysis PowerBI Project
## Project Overview

**Project Title**: Expense Management Analysis  
**Platform Used**: Microsoft Power BI  
**Data Source**: Udemy "Build 45 Real-World Power BI Projects for BI & Data Analysts" Course.

This Power BI project simulates a real-world enterprise finance analytics scenario and focuses on building an integrated financial performance and spend analysis dashboard by modeling, analyzing, and visualizing data across budget, actual spend, and forecast datasets.

## Core Skills Applied

1. Data Cleaning.
2. Data Modeling (Star schema design).
3. Interactive Filters & Slicers.
4. Data Visualization & Dashboard Design.
5. Trend Analysis.

## Problem Statement

ABC Limited (hypothetical) lacks a clear and consistent approach to tracking IT departmental expenses across regions against approved budgets and estimates, limiting visibility into spending trends, key cost drivers, and potential cost overruns.

## Project Structure

### 1. Data Import
- The Budget and Forecast fact tables were imported into Power BI using the Text/CSV connector.
- The Actuals fact table was loaded using the Folder connector.
- All dimension tables were imported using the Excel connector.

![Alt text](./Data%20Import.jpg)

### 2. Data Cleaning
Since my dataset was not clean, I applied several preprocessing steps, including:
- Setting the first row as headers.
- Removing irrelevant columns.
- Updating data types where necessary.

![Alt text](./Data%20Cleaning.jpg)

### 3. Date Table Creation
To ensure consistent and accurate time-based calculations and month-to-month comparisons, I created a date table that included Date, Year, Month, and MonthNumber, tailored to the level of detail required for the analysis.

![Alt text](./Date%20Table.jpg)

### 4. Data Modelling
- My dataset consisted of three fact tables and four normalized dimension tables, which I used to create a galaxy (or fact constellation) schema.

  ![Alt text](./Data%20Modelling.jpg)

  - I also 
