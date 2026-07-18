# Day 4 - Visualizations

Built 5 charts based on the Day 3 pivot tables:

- Monthly Sales Trend (line chart) - shows sales direction over time
- Profit by Region (bar chart) - added a new Target lookup column and Profit pivot to support this
- Sales by Category (pie/bar chart)
- Top 10 Products (horizontal bar chart) - horizontal to fit long product names
- Sales Rep Performance vs Target (clustered column chart) - compares actual sales against each rep's target

Added a Target column to tblOrders via XLOOKUP from tblSalesReps, matched on SalesRepID/RepID. Set the pivot's Target field to Average instead of Sum, since Target is a per-rep value repeated across each rep's orders.

Kept a consistent color scheme across all charts for use in the Day 5 dashboard.
