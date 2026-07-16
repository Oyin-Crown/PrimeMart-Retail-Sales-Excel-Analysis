# Day 2 - Excel Functions

Added helper columns to tblOrders using XLOOKUP:
- CustomerName, Segment (from Customers)
- ProductCategory, CostPrice (from Products)
- IsReturned (from Returns)
- ShipMode (from Shipping)

Calculated columns:
- Profit = Sales - (CostPrice x Quantity)
- OrderMonth = TEXT(Date, "mmm-yyyy")
- ValueFlag = IF(Sales > 1,000,000, "High Value", "Standard")

Practiced separately on a Day2-Practice sheet:
- INDEX + MATCH (as an alternative to XLOOKUP)
- SUMIFS (total sales by region)
- COUNTIFS (count of discounted orders)
- IF / IFS (value flags with multiple tiers)
- IFERROR (catching lookup errors)
- LEFT / RIGHT / MID (extracting numbers from ID codes)
- YEAR / MONTH / WEEKDAY (breaking down dates)
