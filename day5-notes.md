# Day 5 - Dashboard

Built an interactive Dashboard sheet:

- KPI cards: Total Sales, Total Profit, Total Orders, Average Order Value, Return Rate
- Placed all 5 charts from Day 4 in a grid layout
- Added slicers for SalesRepID, Region, ProductCategory, ProductName, and OrderMonth
- Connected each slicer to all relevant pivot tables via Report Connections, so filtering updates every chart at once
- Fixed a data type issue where Date was stored as text rather than a real date, which was blocking pivot/timeline functionality
- Removed gridlines for a cleaner report look
