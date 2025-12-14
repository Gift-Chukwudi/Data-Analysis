# Expense Analysis PowerBI Project
## Project Overview

**Project Title**: Expense Management Analysis  
**Platform Used**: Microsoft Power BI  
**Data Source**: Udemy "Build 45 Real-World Power BI Projects for BI & Data Analysts" Course.  
**Analytics Approach**: Descriptive, focusing on summarizing past data to identify patterns and trends.

This Power BI project demonstrates a real-world descriptive finance analytics scenario by creating an integrated dashboard that summarizes and visualizes historical financial performance and spending patterns. It focuses on modeling and analyzing data across budgets, actual expenditures, and forecasts to reveal trends, variances, and key cost drivers.

## Core Skills Applied

1. Data Cleaning.
2. Data Modeling (galaxy).
3. DAX Formulars.
4. Measures creation.
5. Interactive Filters & Slicers.
6. Data Visualization & Dashboard Design.
7. Trend Analysis.

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

**d. Average Budget**

![Alt text](./Average%20Budget.jpg)

**e. Average Estimate**

![Alt text](./Average%20Estimate.jpg)

### 5. Data Analysis & Visualization
I used purple and pale lilac grey for the background, with black and white for the text, to create a clean, professional look while ensuring strong contrast and readability. I also made use of clear, intuitive visuals so that the dashboard would be easily understood by anyone who viewed it, regardless of their level of expertise.

I used a variety of visuals to highlight key insights from the data, **including:**  

#### a. Card Visuals
Displaying the total number of departments alongside the total estimated amount, budgeted amount, and actual spend.

![Alt text](./Card%20Visuals.jpg)






