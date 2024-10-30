
# Blinkit Sales Report


1.Overview

The Blinkit Dashboard is built in Power BI to provide insights on order patterns, customer behavior, revenue, and platform performance.
This report uses Order and Customer tables to reveal trends and key metrics for decision-making.

2.Key Issues Identified

Order Table Duplicates: Some Order_IDs were duplicated, which could inflate metrics.

Date Issues: Missing or future Order_Date values, which could skew time-based analysis.

Orphaned Orders: Orders without valid Customer_IDs that cannot be linked to any customer.

Customer Table
Duplicate IDs: Some customers have duplicate Customer_IDs, leading to inconsistencies.

Unlinked Customers: Some customers have no corresponding orders, impacting activity metrics.

Inconsistent Formats: Date and data type inconsistencies across tables affected joins and calculations.

Relationship Issues
Missing Links: Some Customer_IDs in Order table do not match any entry in Customer table.

Data Type Mismatch: Differences in data type for Customer_ID across tables disrupted analysis.

3.Data Cleaning Steps

Removed Duplicates: Corrected duplicate Order_ID and Customer_ID entries.

Standardized Dates: Unified date format to YYYY-MM-DD.

Handled Missing Data: Removed orphaned data and corrected inconsistencies.

Timezone Adjustment: Normalized all dates to UTC for accuracy.
Key Dashboard Metrics

Total Orders by Date: Tracks order counts over time.

Revenue Analysis: Revenue breakdown by platform and time period.

Customer Segmentation: Segments based on activity and purchase patterns.

Platform Performance: Insight into app vs. website performance.

Order Fulfillment: Analyzes on-time and delayed orders.

4.How to Use

Open: Load the Blinkit Dashboard.pbix file in Power BI.

Explore: Use tabs to view metrics for orders, customers, and revenue.

Filter: Interact with filters by date, platform, etc., for deeper analysis.


