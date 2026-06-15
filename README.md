# chocolate-sales-analytics-dashboard
An interactive business intelligence dashboard built using Excel and Power BI to analyze global chocolate sales distribution, product margins, and sales team performance.
# Global Chocolate Sales Analytics & Performance Dashboard

## Project Overview
This project transforms disconnected operational business sheets into a centralized, interactive analytics solution using **Power BI** and **Microsoft Excel**. The dataset tracks thousands of transactional shipments for a global chocolate distributor across multiple countries, products, and sales teams. 

The objective of this project was to analyze commercial performance, understand geographic distribution metrics, track regional product popularity, and highlight shipping fulfillment trends.

## Tech Stack & Tools
* **Microsoft Excel:** Source data management and lookup preparation.
* **Power Query:** Data cleaning, attribute mapping, and extraction.
* **Power BI / Excel Dashboards:** Visual report building, custom chart layouts, and interactive filtering.

## Data Structure
The analysis connects several key data areas:
* **Shipments (Fact Table):** Contains transactional rows including `ShipmentID`, `Amount`, `Boxes sold`, `Shipdate`, and `Order_Status` (Delivered, Shipped, Cancelled).
* **Products:** Product breakdown (`PID`, `Product Name`, `Category` like Bars/Bites, and `Cost_per_box`).
* **Geography:** Regional breakdown (`GID`, `Country`, and `Region` like APAC, Americas, Europe).
* **Sales Teams:** Salesperson mapping (`SPID`, `Sales_person Name`, and `Team`).
* **Calendar:** Granular date fields tracking years, months, and specific days of the week.

## Key Features & Insights Developed
1. **Data Aggregation:** Successfully aligned disparate dimension tables to raw shipment lines using strict identifier mapping (`PID`, `GID`, `SPID`).
2. **Order Fulfillment Auditing:** Tracked operational leakage by breaking down revenue streams by fulfillment status, identifying exactly how much potential revenue was lost due to cancelled shipments.
3. **Product & Regional Sales Performance:** Segmented sales metrics to dynamically uncover which product lines (e.g., specific Dark Chocolate Bars or Bites) drove the highest revenues in specific geographic sectors.
4. **Interactive Dashboard Design:** Built a stakeholder-facing visual layer incorporating cross-filtering charts and slicers (by Year, Month, and Region), converting rows of raw statistics into dynamic, clickable insights.

## How to Use this Repository
1. Download the `.xlsx` or `.pbix` project files included in this repository.
2. Open the file to view the interactive dashboard layout.
3. Use the slicers on the side of the dashboard to filter performance instantly by specific markets (APAC, Americas, Europe) or timeframes.
