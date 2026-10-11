[README_PR_2_Analyzer (1).md](https://github.com/user-attachments/files/33296822/README_PR_2_Analyzer.1.md)
# 📘 PR. 2 Analyzer -- Excel Project README

## 1. Project Introduction

**Project Name:** PR. 2 Analyzer\
**Software:** Microsoft Excel\
**Project Type:** Data Analysis and Visualization

### Project Goal

The goal of this project is to analyze sales data using Excel formulas,
summary tables, statistical calculations, charts, and a dashboard. The
results help us understand sales, profit, customer performance, product
categories, regions, and monthly trends.

## 2. Workbook Sheets

The workbook is organized into separate worksheets:

1.  **Dashboard** -- Presents key performance indicators and visual
    summaries.
2.  **Project Instructions** -- Lists the requirements for the project.
3.  **Dataset** -- Contains the sales records and calculated fields.
4.  **Customer Summary** -- Summarizes purchases and profit by customer.
5.  **What-If Analysis** -- Compares estimated profit under different
    discount rates.
6.  **Regression** -- Examines the relationship between sales and
    profit.
7.  **Descriptive Stats** -- Shows statistical summaries of important
    columns.
8.  **Histogram** -- Displays how values are distributed across ranges.
9.  **Monthly Growth** -- Compares monthly sales and growth.
10. **High-Value Customers** -- Identifies customers with the highest
    purchase totals.
11. **Pivot Analysis** -- Compares sales by region and product category.

## 3. Instructions Explained Step by Step

### Step 1: Review the Dataset

Open the **Dataset** sheet. Check the customer, region, product
category, sales, quantity, discount, order date, profit, and timestamp
fields. Make sure the values are correctly formatted.

### Step 2: Use Conditional Formatting

Open **Customer Summary**. Conditional formatting is used to highlight
the top customers so that important values are easy to identify.

### Step 3: Perform What-If Analysis

Open **What-If Analysis**. Compare estimated profit at discount rates
such as 0%, 5%, 10%, 15%, 20%, 25%, and 30%.

The result depends on the assumptions used in the formula. It is a
scenario estimate, not necessarily the actual profit.

### Step 4: Review Regression

Open **Regression**. Review the slope, intercept, R-squared, and
standard error. These measures help describe how sales and profit are
related.

-   **Slope:** Describes the change in predicted profit as sales change.
-   **Intercept:** Predicted profit when sales are zero.
-   **R-squared:** Indicates how much variation in profit is explained
    by the model.
-   **Standard error:** Describes the typical size of prediction errors.

### Step 5: Review Descriptive Statistics

Open **Descriptive Stats**. Measures may include count, mean, median,
standard deviation, minimum, maximum, and range.

-   **Count:** Number of records.
-   **Mean:** Average value.
-   **Median:** Middle value in sorted data.
-   **Standard deviation:** How spread out values are.
-   **Minimum / Maximum:** Smallest and largest values.
-   **Range:** Maximum minus minimum.

### Step 6: Check the Timestamp

The project may use Excel's `NOW()` formula to display the current date
and time:

``` excel
=NOW()
```

This is a dynamic formula, so its result can change when Excel
recalculates the workbook.

### Step 7: Identify High-Value Customers

Open **High-Value Customers**. Review the top 10 customers ranked by
total purchases and use the lookup area, if included, to find a
customer's details.

### Step 8: Compare Regions and Categories

Open **Pivot Analysis**. Compare sales across regions and product
categories. Use the summary to identify the strongest and weakest areas.

### Step 9: Review Charts

Use the charts to interpret the data visually. Read each chart title,
axis labels, legend, and units before drawing a conclusion.

### Step 10: Review the Dashboard

Open **Dashboard** for a quick overview. If slicers are included, select
a slicer value to filter connected PivotTables and charts. Confirm that
the visuals update as expected.

## 4. Charts and What They Show

### 📈 Chart 1: Monthly Sales and Profit

A line chart can compare sales and profit over time.

**How to read it:** The horizontal axis shows months; the vertical axis
shows the amounts. Peaks show stronger months, while drops identify
periods that may need investigation.

### 📊 Chart 2: Sales by Product Category

A column or bar chart compares total sales for each category.

**How to read it:** Taller bars represent categories with higher sales.
This makes it easier to compare product performance.

### 🌍 Chart 3: Sales by Region

A bar chart compares sales across the available regions.

**How to read it:** Compare the bar lengths to identify the highest- and
lowest-performing regions.

### 🥧 Chart 4: Product Category Share

A pie chart can show each category's share of total sales.

**How to read it:** Larger slices represent a larger share of total
sales. Check that the chart uses the same total-sales measure for all
categories.

### 📉 Chart 5: Sales Distribution / Histogram

A histogram groups numeric values into ranges and displays how many
records fall into each range.

**How to read it:** Taller bars show ranges containing more records. The
histogram helps show whether values are concentrated in one range or
spread across many ranges.

> **Important:** The descriptions above explain the purpose of the
> charts. The exact chart titles, values, and appearance should be
> checked in the Excel workbook itself.

## 5. Important Excel Formulas

  -----------------------------------------------------------------------
  Formula                             Purpose
  ----------------------------------- -----------------------------------
  `SUM()`                             Adds numbers.

  `SUMIF()`                           Adds values that meet a condition.

  `COUNTIF()`                         Counts values that meet a
                                      condition.

  `INDEX()`                           Returns a value from a selected
                                      range.

  `MATCH()`                           Finds the position of a matching
                                      value.

  `RANK()`                            Ranks a value against other values.

  `SUMPRODUCT()`                      Multiplies corresponding values and
                                      adds the results.

  `IF()`                              Returns a result based on a
                                      condition.

  `NOW()`                             Returns the current date and time.
  -----------------------------------------------------------------------

## 6. Dashboard Key Performance Indicators

The dashboard may summarize measures such as:

-   **Total Sales** -- Sum of sales values.
-   **Total Profit** -- Sum of profit values.
-   **Total Orders / Records** -- Number of transactions or dataset
    rows, depending on the workbook's definition.
-   **Average Discount** -- Average discount across the included
    records.
-   **Top Region** -- Region with the highest total sales.
-   **Top Category** -- Product category with the highest total sales.

Always confirm that KPI formulas use the correct data range and that the
definition of an order matches the dataset.

## 7. How to Use the Workbook

1.  Open the Excel workbook in Microsoft Excel.
2.  Start with **Project Instructions** to review the requirements.
3.  Review the **Dataset** and check the column headings.
4.  Open each analysis sheet and inspect the calculations.
5.  Review charts and compare the results.
6.  Open the **Dashboard** for the overall summary.
7.  Use available slicers to filter the dashboard.
8.  Save a copy of the workbook before making major changes.

## 8. Final Conclusion

The PR. 2 Analyzer project demonstrates how Excel can be used to
organize data, calculate statistics, compare scenarios, analyze
customers, study sales trends, and communicate results through charts
and a dashboard.

The project supports better understanding of sales performance and helps
identify areas that may need attention. Before submitting, check all
formulas, chart ranges, slicer connections, timestamps, and formatting
against the original project instructions.

## 9. Submission Checklist

-   [ ] All required worksheets are present.
-   [ ] Dataset headings and values are correct.
-   [ ] Formulas calculate without errors.
-   [ ] Customer ranking is correct.
-   [ ] What-If scenarios use the intended assumptions.
-   [ ] Regression and descriptive statistics are complete.
-   [ ] Monthly growth calculations are checked.
-   [ ] Charts have clear titles and labels.
-   [ ] Dashboard charts are neatly arranged.
-   [ ] Slicers, if required, filter the intended charts.
-   [ ] Gridlines and number formats are appropriate.
-   [ ] Workbook is saved and ready for submission.
