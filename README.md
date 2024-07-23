# SuperStore Sales Dashboard
<br>

# Table of Contents

1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Data Cleaning](#data-cleaning)
4. [Pivot tables](#pivot-table-analysis)
    * [Total Sales Over Time](#total-sales-over-time)
    * [Total Sales by Region](#total-sales-by-region)
    * [Percentage Share by Category](#percentage-share-by-category)
    * [Top 5 Sub-Categories](#top-5-sub-categories)
    * [Top 5 Customers](#top-5-customers)
5. [Dashboard](#dashboard)
<br>

# Introduction
Dataset Name: SuperStore Sales Dataset.
<br>

source: kaggle 
<br>
link: [Superstore Sales Dataset](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting)
<br>

# Dataset

![alt text](images/Dataset.jpg)

This dataset contains 18 columns and 9801 rows.<br>
# Data Cleaning
This analysis is based on only the columns shown in the fig. below.

![alt text](images/Mydataset.jpg)
The overall dataset is already cleaned.
Let’s convert it into a table and do further analysis.

![alt text](images/SuperStoreTable.jpg)
<br>

# Pivot Table Analysis

## Total Sales Over Time

![alt text](images/TotalSalesOverTime1.jpg)

This table looks good but let’s modify it a little bit. We want to see sales based on the month and the year.<br> 
First, group the Row Label column based on year and month.

![alt text](images/Top10Statesfiler.jpg)
<br>

![alt text](images/TotalSalesOverTimeMonthsandYear.jpg)
<br>
Also, remove totals and Subtotals from the pivot table.

![alt text](images/TotalSalesOverTimeformat.jpg)

Create a line chart to show the sales trend over the years.

![alt text](images/TotalSalesOverTimeLineChart.jpg)

Then we will insert all the necessary slicers:
Time Line Slicer:
![alt text](images/TimeLine.jpg)

Similarly, we will insert a slicer for the region, year, segment category, sub-category, ship mode and state.
<br>
## Top 10 States based on Sales

![alt text](images/Top10States.jpg)

Add a value filter to show only the top 10 states based on the sales and then create a bar chart.

![alt text](images/Top10Statesfiler.jpg)

Format the sales number to US currency and remove the decimals. Insert a column chart to show the states.

## Total Sales by Region

![alt text](images/SalesByRegion.jpg)

## Percentage Share by Category
![alt text](images/popularitySharepiechart.jpg)

## Top 5 Sub-Categories

![alt text](images/Top5subcategories.jpg)

## Top 5 Customers

![alt text](images/Top5Customers.jpg)<br>

# Dashboard

![alt text](images/Dashboard.jpg)