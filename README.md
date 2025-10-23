# Retail-Footfall

Project Overview

Footfall Monitor is a Power BI dashboard designed to track and analyze retail footfall across multiple regions, cities, and calculation types.
It helps visualize visitor patterns, compare year-on-year performance, and identify key trends across selected time periods.

- Data Source

Primary dataset: Footfall Monitor table

Key columns:

Location, Region, City

Calculation Type

Footfall

Month, Year, Week Number

The dashboard dynamically calculates KPIs like Retail Footfall (Region Comparison), Change in Rank, and Total Retail Footfall.

- Features

Dynamic date-based calculations (Month, Quarter, and Year comparisons)

Conditional formatting for positive/negative footfall

Measures to compare selected vs previous periods

Integration with Power BI visuals:

Card visuals for summary KPIs

Matrix visuals for rank and change analysis

Line and clustered column charts for trend comparison

- Update Notes

Added Footfall Monitor .pbix file – latest version includes:

Updated DAX measures for dynamic month comparison

Fixed conditional formatting issue (negative values now retain red color)

Improved performance by removing redundant calculated columns

The dataset now supports linking with a Date dimension via selected_period_to column.
