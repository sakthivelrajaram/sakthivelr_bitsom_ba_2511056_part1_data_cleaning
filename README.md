# Part 1: Business Data Cleaning, Validation & Excel Reporting

## Problem Summary

The dataset contains inconsistencies such as missing values, duplicate records, incorrect date formats, and invalid discounts. The objective is to clean and validate the dataset to make it suitable for business analysis.

## Dataset Description

The dataset includes retail order-level data such as customer details, product categories, sales, profit, shipping details, and order status.

## Tools Used

* Microsoft Excel

## Cleaning Steps Performed

* Removed extra spaces using TRIM
* Standardized text fields using PROPER
* Converted order_date and ship_date into proper format
* Handled missing values (region, ship_mode)
* Identified and handled duplicates
* Validated discount values

## Business Rules Applied

* Missing region filled as "Unknown"
* Missing ship_mode filled as "Unknown"
* Negative discounts flagged as invalid
* Ship date earlier than order date flagged
* Cancelled and failed orders excluded from final analysis

## Data Quality Issues Found

* Missing values in region and ship_mode
* Invalid date formats
* Negative discount values
* Duplicate records present

## Pivot Summary

* Sales by region
* Profit by category
* Orders by ship mode
* Monthly sales trend

## Key Business Insights

* Certain regions contribute higher sales
* Some categories generate higher profit margins
* Shipping delays impact delivery performance

## Assumptions

* Missing discount treated as 0 where applicable
* Unknown values used for missing categorical data

## Limitations

* Some manual cleaning assumptions applied
* No advanced statistical imputation used

## Screenshots

Screenshots are included in the screenshots folder.
