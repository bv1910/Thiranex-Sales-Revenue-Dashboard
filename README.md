# Sales & Revenue Analysis Dashboard (Power BI)
Thiranex Internship – Task 1

## Dataset
Superstore sales data: 9,800 order lines, Jan 2015 – Dec 2018 (Sales only, no profit column).

## Steps
- Cleaned data in Power Query (date types with UK locale, removed unused columns, filled missing postal code)
- Built a Date table and related it to Order Date
- DAX measures: Total Sales, Total Orders, Total Customers, Avg Order Value, Sales LY, YoY Growth %
- Visuals: KPI cards, monthly sales trend, Top 10 products, sales by category, sales by region, year-wise growth table, slicers for Year/Region/Category

## Key Insights
- Total sales of ~$2.26M from 4,922 orders and 793 customers; average order value ~$459
- Sales dipped 4.3% in 2016, then grew 30.6% in 2017 and 20.3% in 2018
- Technology is the top category ($827K), but all three categories are close
- West and East regions bring in ~61% of sales; South is the weakest
- Sales peak in Sep, Nov and Dec, so the year-end is the busiest season
- Canon imageCLASS 2200 Advanced Copier is the top product, earning more than twice the next one
