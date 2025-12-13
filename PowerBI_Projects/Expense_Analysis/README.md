# Expense Analysis PowerBI Project
## Project Overview

**Project Title**: Expense Management Analysis  
**Platform Used**: Microsoft Power BI  
**Data Source**: Udemy "Build 45 Real-World Power BI Projects for BI & Data Analysts" Course.  
**Analytics Approach**: Descriptive, focusing on summarizing past data to identify patterns and trends.

This Power BI project simulates a real-world enterprise finance analytics scenario and focuses on building an integrated financial performance and spend analysis dashboard by modeling, analyzing, and visualizing data across budget, actual spend, and forecast datasets.

## Core Skills Applied

1. Data Cleaning.
2. Data Modeling (galaxy).
3. Interactive Filters & Slicers.
4. Data Visualization & Dashboard Design.
5. Trend Analysis.

## Problem Statement

ABC Limited (hypothetical) lacks a unified system for analyzing historical IT departmental expenses across regions, making it difficult to clearly visualize spending patterns, identify major cost drivers, and understand trends in relation to approved budgets and estimates.

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

  - I created 9 measures to ensure accurate values in the visuals.

**a. Average Spend**

![Alt text](./Average%20Spend.jpg)

**b. vs. Last Month:** I created this measure to effectively display the percentage change in values on the card compared to the previous month.
**Note:** *I also created this measure for budget and estimate card visuals.*

![Alt text](./vs%20Last%20Month.jpg)

**c. vs. Last Month %:** I created this measure to apply conditional formatting to the previous measure, displaying the percentage in green for positive values and red for negative values.
**Note:** *I also created this measure for budget and estimate card visuals.*

![Alt text](./Color%20Formatting.jpg)

![Alt text](./Color%20Formatting.jpg)



