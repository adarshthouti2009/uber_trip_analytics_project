# Uber Trip Analysis

## Description 

The Uber Trip Analysis Dashboard aims to provide comprehensive insights into Uber's trip performance, booking trends, revenue generation, and trip efficiency. By leveraging Power BI, the dashboard facilitates data-driven decision-making, helping stakeholders optimize operations, pricing strategies, and customer satisfaction.

## DASHBOARD 1: OVERVIEW ANALYSIS

### KPI Metrics

1. Total Bookings – Number of trips booked over a period.
2. Total Booking Value – Total revenue generated from bookings.
3. Average Booking Value – Average revenue per booking.
4. Total Trip Distance – Total distance covered by all trips.
5. Average Trip Distance – Average trip distance per ride.
6. Average Trip Time – Average duration of trips.

### Expected Outcomes

* Identify trends in bookings and revenue.
* Analyze trip efficiency in terms of distance and time.
* Compare booking metrics across different time periods.
* Drive insights for pricing strategies and customer satisfaction.

### Charts and Visualizations

a. Dynamic Measure Selector: Created using a disconnected table with:

  * Total Bookings
  * Total Booking Value
  * Total Trip Distance

b. Segmentation Dimensions:

  * By Payment Type (Card, Cash, Wallet, etc.)
  * By Trip Type (Day/Night)

### Additional Enhancements

  * Dynamic Title: Automatically updates based on selected measure.
  * Slicers: Filters for Date, City, etc.
  * Tooltips: Show detailed insights (e.g., Avg Booking Value).

### Vehicle Type Analysis - Grid View

  * Display KPIs by vehicle type using Table or Matrix visuals.
  * Conditional formatting for value insights.
  * Enable sorting/filtering for interaction.

### Total Bookings by Day

  * Detect trends and fluctuations in daily bookings.
  * Identify peak/off-peak days.
  * Assess external impact (weather, events, holidays).

### Location Analysis

  * Most Frequent Pickup/Drop-off Points: Identify common trip locations.
  * Farthest Trip: Analyze long-distance rides.
  * Total Bookings by Location (Top 5): Identify highest-demand locations.
  * Most Preferred Vehicle by Pickup Location: Optimize vehicle distribution.

### Implementation Enhancements

  * Bookmark: Data Details
  * Metric definitions, source description, refresh frequency.
  * Clear Slicer Button: Reset all filters with one click.
  * Download Raw Data Button: Export raw data using Power Automate or Power BI export functionality.

## DASHBOARD 2: TIME ANALYSIS

### Objective

Understand trip patterns based on time to optimize operations, pricing, and driver distribution.

1. Dynamic Measure (Global)
    Selector for:
    * Total Bookings
    * Total Booking Value
    * Total Trip Distance

2. Visualizations

    * By Pickup Time (10-minute Intervals): Area Chart to show daily demand trends.
    * By Day Name (Mon–Sun): Line Chart to compare weekday vs. weekend trends.
    * By Hour & Time (Heatmap):
    * Rows: Hours of the Day (0–23)
    * Columns: Days of the Week (Mon–Sun)
    * Values: Selected Dynamic Measure
    * Insight: Highlights peak demand times.

## DASHBOARD 3: DETAILS TAB

### Objective

Provide granular insights and support drill-through functionality for in-depth data analysis.

### Features

  * Grid Table: Display essential trip fields.
  * Drill-Through Functionality: Right-click from other charts to explore detailed trip records.
  * View Full Data Bookmark: Toggle between filtered view and complete dataset.

## Conclusion

This structured and interactive Power BI solution empowers Uber stakeholders to derive actionable insights from trip data and enhance operational strategies efficiently.
