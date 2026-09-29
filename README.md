# Power BI Dashboards: Sales Analysis & EY Business Analytics

Interactive Power BI dashboards that let a business user monitor revenue, trends and category performance at a glance.

## Files
| File | Description |
|---|---|
| `Dashboard for Sales Analysis.pbix` | Sales performance dashboard built on `sales_data.xlsx` |
| `EY_DASHboard.pbix` | Dashboard built during the EY Business Analytics & Descriptive Analysis course on `EY_data.xlsx` |

## What the dashboards show
- **KPI cards:** Total Revenue, Total Orders/Quantity, Average Order Value *[edit to match your cards]*
- **Trend analysis:** revenue over time (line chart)
- **Category / region performance:** bar and column charts
- **Slicers:** interactive filters for date, region and category

## How it was built
1. **Power Query:** imported the Excel data, set data types, removed blanks and duplicates, renamed columns.
2. **Data model:** related tables where needed.
3. **DAX measures:** e.g. `Total Revenue = SUM(Sales[Revenue])`.
4. **Visuals and design:** KPI cards on top, trends in the middle, breakdowns below, with slicers for interactivity.

## Screenshots
*Add a PNG screenshot of each dashboard page here. Recruiters cannot open .pbix files in the browser, so screenshots matter.*

## Tools
Power BI Desktop · Power Query · DAX · Microsoft Excel
