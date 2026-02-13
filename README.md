# BrewMetrics Dashboard

<p align="center">
  <img src="dashboard_logo.png" alt="BrewMetrics Logo" width="200">
</p>

## Overview
BrewMetrics is a comprehensive coffee sales analysis dashboard built in Microsoft Excel. It provides actionable insights into sales performance, customer preferences, and operational efficiency for a multi-state coffee business.

The dashboard transforms raw sales data into interactive visualizations, allowing stakeholders to monitor key metrics and make data-driven decisions.

## Key Features
- **Sales Performance Analysis**: Track sales across different coffee types, including Americano, Cappuccino, Flat White, Iced Latte, and more.
- **Geographic Insights**: Visualize sales distribution across major states: California, Texas, New York, Florida, and Illinois.
- **Operational Efficiency**:
    - **Busy Hours Heatmap**: Identify peak operational times by hour and day of the week.
    - **Wait Time Analysis**: Monitor average customer wait times to optimize staffing.
- **Customer Segmentation**: Analyze sales based on customer types and sales channels (In-store vs. Online).
- **Quality Control**: Track order ratings to ensure consistent product quality and customer satisfaction.
- **Interactive Slicers**: Filter the entire dashboard by State, Coffee Type, and Sales Channel for granular analysis.

## Dataset Description
The dashboard is powered by the `Coffee_Sales_Dataset` sheet, which contains 1,000 detailed order records with the following attributes:
- **Date & Time**: When the order was placed (Date, Workday, Hour).
- **Location**: State where the sale occurred.
- **Product Details**: Coffee type and price per unit.
- **Transaction Details**: Sales channel, payment method, and promotion applied.
- **Operational Data**: Barista name and wait time.
- **Customer Feedback**: Customer type, special requests, and order rating.

## How to Use
1. **Open the File**: Open `Coffee_Insight_Dashboard.xlsx` in Microsoft Excel.
2. **Navigate to the Dashboard**: Go to the **Dashboard** sheet to view the primary visualizations.
3. **Interact**: Use the **Slicers** (Filter buttons) on the dashboard to drill down into specific data points.
4. **Data Refresh**: If the underlying dataset is updated, go to the **Data** tab and click **Refresh All** to update all pivot tables and charts.

## Author
**Siddhant Singh**
