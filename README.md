# Task 3 – Interactive Sales Dashboard (Power BI)
The goal of this task was to design an **interactive sales dashboard** using Power BI for business stakeholders. The dashboard provides a clear overview of sales performance across multiple dimensions such as product categories, sales channels, regions, and order status.
# Tools Used
- **Power BI** – For data analysis and visualization
- **Excel/CSV** – For raw data
- **Google Drive** – To host large dataset file
- **GitHub** – For sharing code and dashboard assets
## Dataset
The dataset used for this task is an **Amazon Sales Report**, which includes fields like:
- `Amount` – used as the Sales value
- `Qty` – quantity of items sold
- `Category`, `Style`, `Size` – product details
- `ship-country`, `ship-state` – shipping location
- `Sales Channel`, `Fulfilled-by` – platform & logistics data
- `Courier Status`, `Status` – order delivery details
- `date` – used for time-series sales analysis

## Dashboard Features
- **KPI Cards**:
  - Total Sales (₹)
  - Total Orders
  - Total Quantity Sold

**Time-Series Analysis**:
  - Sales trend over time (using `date` vs `Amount`)
**Category-wise Sales**:
  - Bar and pie charts for product category performance
**Region-wise Sales**:
  - State-wise sales performance using bar charts
**Fulfillment and Sales Channel Breakdown**:
  - Analysis of how orders were fulfilled and through which channel
**Courier Status Overview**:
  - Breakdown of order delivery statuses
**Interactive Filters (Slicers)**:
  - Filter visuals by Category, Region, Sales Channel, and Date

## Key Insights
- The majority of sales are concentrated in a few top product categories.
- Certain regions contribute significantly more to total revenue.
- Most orders are fulfilled by a specific method, indicating logistics trends.
- Order delivery status reveals a percentage of pending or returned shipments.

