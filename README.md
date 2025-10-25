Special thanks to Baraa Khatib Salkini for the tutorial that guided the dashboard build.
**Project:** Interactive Tableau dashboard for HR

# hr-dashboard-LP (learning project)
A polished, dark-themed HR dashboard - Overview workspace (Overview / Demographics / Income) and Employee List detailed. 
Designed for HR managers to get fast executive insight and then drill to individual employees.

## Overview
A compact, interactive HR dashboard that gives HR managers a fast executive snapshot plus drill-down employee detail. 
The workbook is organized into Summary (Overview, Demographics, Income) and Employee Records tabs so users can move from high-level trends to individual records.

![lego-report](screenshots/short-interactivity.gif)

## Key Features
- **KPI Overview:** Total Sales, Total Profit, Total Quantity — current year vs prior year.  
- **Monthly Trends:** Monthly breakdowns for KPIs with highest/lowest months highlighted.  
- **Product Subcategory Comparison:** Side-by-side view of sales and profit by subcategory (YOY).  
- **Weekly Trends:** Weekly sales & profit with average lines and highlight for above/below-average weeks.  
- **Customer Insights:** Total customers, sales per customer, distribution of customers by number of orders, and Top-10 customers by profit (rank, orders, sales, profit, last order date).  
- **Interactivity:** Year selector, category/subcategory filters, region/state/city filters, and clickable charts for drill-downs.

## Files in this repository
- `datasets/` — uncleaned sample dataset used for the dashboard  
- `README.md` — this file  
- `screenshots/` — images of the dashboard for quick preview

## How to open / use
1. click tableau publick link
   link: tableau public (https://public.tableau.com/app/profile/rowel.andrew.legaspi/viz/SalesDashboard_17568891806350/SalesDashboard)

## Design & UX notes
- KPI cards show current year value and percent change vs prior year.  
- Monthly line charts include markers for highest and lowest months for quick visual scanning.  
- Weekly charts are split into two panes (Sales / Profit) with dashed lines to show average and colors to indicate above/below average performance.  
- Product subcategory view uses horizontal bars for easy comparison and an adjacent profit bar to show margin impact.  
- Top 10 customers panel includes rank, order count, sales, profit, and last order date to help identify high-value and dormant accounts.


## Contact
Rowel Andrew Legaspi (Drew)  
- LinkedIn: https://www.linkedin.com/in/rowel-andrew-legaspi-289936241/
- Tableau Profile: https://public.tableau.com/app/profile/rowel.andrew.legaspi
