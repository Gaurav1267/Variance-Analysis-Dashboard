# Variance Analysis Dashboard

This repository contains a dynamic Variance Analysis Dashboard, to provide a clear and insightful comparison between budgeted and actual financial figures for income and expenses. The dashboard helps users quickly identify areas of financial overperformance or underperformance.


## Overview

The Variance Analysis Dashboard is built in Microsoft Excel and allows users to select a month to view detailed financial performance. It highlights variances (absolute and percentage) for various income and expense categories, complemented by visual charts for easier interpretation.

## Features

* **Dynamic Month Selection:** Easily switch between months (e.g., using a button or dropdown) to view the variance analysis for specific periods.
* **Income Variance Analysis:** Detailed breakdown of budgeted vs. **actual** income for categories like Base Salary, Bonus, and Side Hustle, including absolute and percentage variances.
* **Expenses Variance Analysis:** Comprehensive comparison of budgeted vs. **actual** expenses across various categories such as Rent, Utilities, Transport, Groceries, Leisure, and Other, with absolute and percentage variances highlighted.
* **Actuals Data Integration:** The dashboard directly pulls and displays your actual income and expense data from a dedicated sheet, allowing for a real-time comparison against your set budget.
* **Visualizations:**
    * **Budget vs Actuals Income Chart:** A bar chart illustrating the budgeted and actual amounts for different income streams.
    * **Actual Expenses Breakdown:** A pie chart providing a clear proportional view of **actual** spending across expense categories.
* **Savings Calculation:** Displays the budgeted, actual, and variance for savings, offering insights into financial surplus or deficit.

## How to Use

1.  **Download/Open the Excel File:** Clone this repository or download the Excel file directly.
2.  **Update Actuals Data:**
    * Navigate to the `Actual Income & Expenses 2022` sheet.
    * Ensure this sheet is updated with your latest financial transactions (income and expenses) for the relevant months. The dashboard relies on this data for its `Actual` figures.
3.  **Navigate to the Dashboard:** Go to the `Budget vs. Actual Dashboard` sheet.
4.  **Select a Month:** Use the month selector (e.g., the 'May' button or a dropdown if implemented differently) to choose the period you wish to analyze.
5.  **Review Variances:** Examine the `Var. Abs` (Absolute Variance) and `Var. %` (Percentage Variance) columns for both income and expenses to pinpoint deviations between your budget and your **actual** spending/earnings.
6.  **Analyze Visualizations:** Utilize the "Budget vs Actuals Income" bar chart and "Actual Expenses Breakdown" pie chart to gain quick insights into **actual** income performance and **actual** expense distribution compared to the budget.

## Data Sources

The dashboard is dynamically populated using data from the following supporting sheets within the Excel workbook:

* `Budgeted Income & Expenses 2022`: Contains the planned financial figures for each month of the year.
* `Actual Income & Expenses 2022`: Holds the detailed, transaction-level records of actual income and expenses.

## Project Goals

* To demonstrate proficiency in data analysis, data modeling, and visualization within a spreadsheet environment.
* To create an intuitive and dynamic financial monitoring tool for personal finance.
* To enable quick identification of financial deviations from the budget, aiding in better financial planning and control.

## Technologies/Tools Used

* **Microsoft Excel** (or compatible spreadsheet software like Google Sheets, LibreOffice Calc)
* Excel Formulas (e.g., `SUMIF`, `INDEX-MATCH`, etc. for data retrieval and calculations)
* Data Validation (for month selection)
* Conditional Formatting (for visual emphasis on variances)
* Charts (Bar Charts, Pie Charts)


---
