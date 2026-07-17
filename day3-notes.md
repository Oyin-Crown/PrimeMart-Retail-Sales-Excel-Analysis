# Day 3 - Pivot Tables

Built 6 pivot tables from tblOrders:

- Sales by Region
- Sales by Category
- Sales by Sales Representative
- Sales by Month
- Top 10 Customers
- Top 10 Products

Fixed a data range issue where pivots were picking up empty rows beyond the actual dataset, showing as a "(blank)" group with no value. Rebuilt pivots referencing the table (tblOrders) directly instead of a fixed cell range to resolve it.
