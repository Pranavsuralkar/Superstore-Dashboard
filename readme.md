Superstore Sales Dashboard – Power BI  

\#\# Project Overview    
This project presents an interactive Power BI dashboard built using the Superstore dataset. The dashboard provides insights into sales, profit, returns, discounts, and customer segments, along with a region-wise drilldown for decision-making.  

The dashboard is divided into two pages:    
1\. Executive Overview – High-level KPIs, trends, and performance analysis.    
2\. Region-wise Insights – Detailed breakdown by region, state, and city with manager-level accountability.  

\---

\#\# Dataset    
The project uses the Sample Superstore dataset (Excel file).    
\- Orders → Sales transactions with product, customer, and shipping details.    
\- Returns → Returned orders.    
\- People → Regional managers mapping.  

\#\# Data cleaning was minimal since dataset is mostly clean.    
\- Verified column data types (Date, Number, Text).    
\- Created a Date table for time intelligence.    
\- Built relationships:    
  \- \`Returns\[Order ID\]\` → \`Orders\[Order ID\]\`    
  \- \`People\[Region\]\` → \`Orders\[Region\]\`  

\---

\#\#  Steps to Build  

1\. Data Import – Load Superstore dataset into Power BI.    
2\. Data Modeling   
   \- Created relationships between tables.    
   \- Built Date table with Year, Month, Quarter.    
   \- Marked as official Date table.    
3\. Measures (DAX)    
   \- Sales, Profit, Orders, Discount, Profit Margin %.    
   \- Returns-related metrics (Return Rate %).    
   \- Time intelligence (YoY, Last Year Sales/Profit).    
4\. Visuals   
   \- Page 1 (Overview): KPIs, Sales Trends, Profitability, Discounts, Returns, Customer Segments.    
   \- Page 2 (Region-wise): Regional KPIs, Drilldowns (Region → State → City), Manager performance, Maps.    
5\. Formatting & Layout   
   \- Canvas size: 16:9 (1280x720).    
   \- Consistent colors for Sales (blue), Profit (green/red), Returns (orange).    
   \- Titles, slicers, and filters for better interactivity.  

\---

\#\#  Dashboard Features  

\#\# Page 1 – Executive Overview    
\- KPI Cards: Total Sales, Profit, Orders, Profit Margin %, Return Rate %.    
\- Sales Trend with YoY comparison.    
\- Sales by Category/Sub-Category.    
\- Segment-wise Profitability.     
\- Discount vs Profit Margin analysis.    
\- Return rate by Category.  

\#\#Page 2 – Region-wise Insights    
\- Regional KPIs (Sales, Profit, Return Rate, Regional Manager).    
\- Sales & Profit Margin by Region.    
\- Drilldown hierarchy: Region → State → City.    
\- Region-wise Category contribution.    
\- Monthly Sales Trend for selected region.   

\--TU2nnzh20xs1Nt02l+H3s2DHtoRgVLHBmKMjkt23bSrt37aLq6mqRCLw8PcXkph+8/55e4MyfP09k+qgCxVcAljHMTAZxH8NytXF/0cKF+riPAkDG/bCwE2IfhAzjjCBfzs/PJy8vL2psbBRxF0Oovb0PijgsBc7nn88S4gf5PMfpyWGB42J0dHSMK/wK7SqGcWliY2M57jMuRVpaGu3ZvVu7mLEQFjguBr5snWV+KIaxJ+ijwHGfcSXQB4f72UwdFjgMwzAMw7gc/x96c8L6LcY/6AAAAABJRU5ErkJggg==>
