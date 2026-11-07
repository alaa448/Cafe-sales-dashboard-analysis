# Star Cafe Performance Analysis Dashboard
![Star Cafe Dashboard](cofe%20sales-dashboard-analysis/image/dashboard.png)
## Executive Summary
This dashboard provides a comprehensive overview of "Star Cafe's" operational performance. It highlights key metrics regarding sales volume, customer preferences, and temporal trends to drive data-informed decisions.

> **Tools Used:** Microsoft Excel, Power Query (Data Cleaning), Power Pivot & DAX (Analysis).

---
## Key Performance Indicators (KPIs)
- **Total Sales:** $42,627.58 in revenue.
- **Total Orders:** 1,313 orders processed.
- **Menu Diversity:** 8 distinct items on the menu.
- **Average Order Value (AOV):** ~$32.46 per order.

---

## Product Performance
- **Top Sellers:** 
  - 1 **"Americano With Milk"** (319 orders)
  - 2 **"Latte"** (262 orders)
  - *Insight:* Milk-based coffee drinks are the primary revenue drivers, accounting for nearly 45% of total orders.
- **Underperformers:** 
  - "Cocoa" (44 orders) and "Espresso" (69 orders) are the least popular items.

---

## Temporal Analysis
### Weekly Trends
- **Busiest Days:** Sunday (206) and Thursday (206), followed by Saturday (189).
- **Slowest Day:** Monday (77 orders) is significantly quieter.

### Monthly Trends
- **Peak Month:** May recorded the highest volume (267 orders).
- **Low Month:** August saw a dip to 158 orders.

### Shift & Payment Insights
- **Peak Hours:** The **Morning shift** is the busiest with 510 orders, suggesting a strong breakfast/commuter crowd.
- **Payment Preference:** 93% of payments are made via **Card**, indicating a high reliance on digital transactions.

---

## Strategic Recommendations
Based on the data insights, here are actionable steps to optimize operations:

### 1. Menu & Inventory Optimization
- **Secure Top Sellers:** Ensure consistent stock of high-quality beans and milk for "Americano With Milk" and "Latte".
- **Revamp Low Performers:** Investigate why "Cocoa" and "Espresso" are underperforming. Consider bundling them with pastries or replacing them with seasonal items.

### 2. Marketing & Sales Strategies
- **"Monday Boost" Campaign:** Launch targeted promotions (e.g., "Monday Morning Special") to drive traffic on the slowest day.
- **Upselling in Peak Hours:** Train staff to suggest add-ons (croissants/muffins) during the busy Morning shift to increase AOV without slowing service.

### 3. Operational Efficiency
- **Staff Scheduling:** Align staffing with peak hours. Allocate maximum baristas during the Morning shift (510 orders) to reduce wait times.
- **Digital Infrastructure:** Ensure POS systems are fast and reliable given the 93% card usage rate to prevent lost sales during rushes.

---

## Technical Details
- **Data Cleaning:** Performed using **Power Query** to handle missing values and standardize formats.
- **Data Modeling:** Built using **Power Pivot** with relationships between Sales, Products, and Time tables.
- **DAX Measures:** Created dynamic measures for Total Sales, YoY Growth, and AOV.

## How to Use
1. Download the `cofe dash final.xlsx` file.
2. Open it in Microsoft Excel.
3. Click **Enable Content** if prompted.
4. Go to the **Data** tab and click **Refresh All** to update the dashboard with any new data.
