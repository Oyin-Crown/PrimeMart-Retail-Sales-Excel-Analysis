# Day 1 - Data Cleaning

- Checked Orders, Customers, Products, SalesReps for duplicates: none found
- Checked for blank cells: Reason column in Returns was blank for all orders with Returned = No, which is expected (no reason needed if nothing was returned)
- Formatted Date columns consistently (yyyy-mm-dd) across Orders, Shipping (ShipDate, DeliveryDate)
- Formatted currency columns (Sales, CostPrice, SellingPrice, Target) as Naira (₦#,##0)
- Converted all 6 ranges to Excel Tables: tblOrders, tblCustomers, tblProducts, tblSalesReps, tblReturns, tblShipping
- Verified relationships between CustomerID, ProductID, SalesRepID and their lookup sheets: all returned 1, no broken links
