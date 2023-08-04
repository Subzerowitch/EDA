# EDA

# Adidas US Sales Analysis

## Introduction

This project analyzes the sales data of Adidas in the USA to identify trends and patterns in total sales, units sold, and other variables. The data is sourced from the 'Adidas US Sales Datasets.xlsx' file, and the analysis is performed using Python with libraries such as Pandas, Matplotlib, Seaborn, and Scikit-learn.

## Data Cleaning

The first step of the analysis involves data cleaning to ensure that the data is in the correct format and ready for analysis. The following data cleaning steps were performed:

1. Removed blank rows in the header to exclude the logo and reset indexation.
2. Reset column names to appropriate values.
3. Changed column data types from object to int for numeric values.
4. Changed 'Retailer' ID to a float data type.
5. Converted object data to datetime dtype for datetime values.
6. Converted object data to float dtype for 'Operating Margin' values.

## Exploratory Data Analysis (EDA)

After data cleaning, the EDA process was performed to gain insights into the sales data. The EDA includes the following visualizations:

1. Correlation Matrix Heatmap: To identify the correlation between numerical variables like 'Total Sales,' 'Units Sold,' and 'Operating Profit.'
2. Line Chart Visualization of 'Total Sales 2020-2021': To determine trends and patterns in total sales over the two years.
3. Line Chart Visualization of 'Units Sold 2020-2021': To observe trends in the number of units sold over the two years.
4. Bar Chart Visualization of 'Online/Offline Sales': To compare online and offline sales over the two years.
5. Pie Chart Visualization of 'Percentage of Online and Offline Sales': To represent the percentage of online and offline sales from the total sales.
6. Pie Chart Visualization of 'Percentage of Total Sales Made by Retailer': To illustrate the percentage of total sales contributed by each retailer.
7. Pie Chart Visualization of 'Percentage of Total Sales Made in Each Region': To show the percentage of total sales in each region.
8. Pie Chart Visualization of 'Percentage of Total Sales of Region of Each Retailer': To represent the percentage of total sales for each retailer in each region.
9. Bar Chart Visualization of 'Units Sold vs Product Type': To visualize the number of units sold for each product type.
10. Bar Chart Visualization of 'Total Sales Comparison 2020 vs 2021': To compare the total sales of the two years.

## Trend Analysis

Trend analysis was performed on total sales to identify the factors affecting sales growth. Growth rates for each month of 2021 in comparison to 2020 were calculated. The results are plotted in a line chart to visualize the sales trend.

## Simple Linear Regression

A simple linear regression model was applied to the data to understand the relationship between 'Units Sold' and 'Operating Profit.' The model was fitted, and the slope and intercept values were obtained. The data points and the fitted line are plotted to visualize the linear regression.

## Data Export

The cleaned and analyzed data was exported to Excel files for further use in Tableau. The following datasets were saved:

1. 'monthly_sales.xlsx': Monthly total sales data.
2. 'state_total_sales.xlsx': Total sales for each state.
3. 'state_total_units_sold_df.xlsx': Units sold in each state.
4. 'state_sales_units.xlsx': Combined dataset of state total sales and units sold.
5. 'sales_method_df.xlsx': Online and offline sales data.
6. 'monthly_sales_units.xlsx': Monthly units sold data.
7. 'onlineOffline.xlsx': Dataset for online and offline sales comparison.
8. 'group_by_retailer_df_general.xlsx': Total sales made by each retailer.
9. 'product_sales.xlsx': Units sold by product type.
10. 'monthly_sales20_comparison.xlsx': Monthly total sales data for 2020.
11. 'monthly_sales21_comparison.xlsx': Monthly total sales data for 2021.

## Conclusion

The analysis provides valuable insights into the sales trends of Adidas in the USA. The visualizations help identify the factors influencing sales growth and the performance of different products, retailers, and regions. The linear regression model reveals the relationship between 'Units Sold' and 'Operating Profit.' The exported datasets are ready for further analysis and visualization in Tableau.
