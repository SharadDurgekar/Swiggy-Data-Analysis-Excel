# Swiggy Data Analysis — Advanced Excel

## Project Overview

This project analyses Swiggy restaurant and dish-level data using Microsoft Excel to identify sales patterns, restaurant performance, pricing trends, geographic patterns and potential business drivers.

The objective was not just to create a dashboard, but to use data analysis to answer meaningful business questions and communicate actionable insights.

## Tools Used

- Microsoft Excel
- PivotTables
- PivotCharts
- Slicers
- Excel formulas
- Scatter plots
- Trendlines
- R² analysis
- Data visualization

## Dataset

The dataset contains approximately 197K restaurant/dish-level records with information including:

- Restaurant
- City
- State
- Food Type
- Category
- Price
- Rating
- Rating Count
- Dish Name
- Date-related fields

## Key Analysis

### Sales Analysis
- Monthly sales trends
- Quarterly performance
- Weekly sales trends
- Day-of-week performance

### Geographic Analysis
- State-wise sales
- City-wise sales
- Sales contribution by state

### Restaurant Analysis
- Top 10 restaurants by sales
- Restaurant performance
- Average price per dish/record

### Business Driver Analysis
- Restaurant Rating vs Sales
- Dish/Record Count vs Sales
- Average Price per Dish/Record

## Key Insights

- Karnataka recorded the highest state-level sales contribution.
- The top 5 states contributed approximately 32.90% of the dataset's aggregate price-based sales measure.
- The top 10 restaurants accounted for approximately 34.16% of the aggregate sales measure.
- Restaurant rating showed virtually no linear relationship with sales (R² ≈ 0.0002).
- Dish/record count showed a very strong positive relationship with the aggregate sales measure (R² ≈ 0.9762).

## Dashboard

The project includes an interactive Excel dashboard with KPIs, charts, geographic analysis and business-driver analysis.

## Important Data Note

The dataset does not contain a unique Order ID or transaction-level order information.

Therefore, the project's "Sales" measure is based on the sum of the `Price (INR)` field across dataset records and should not be interpreted as Swiggy's actual revenue or transaction sales.

Similarly, "Dish/Record Count" represents records in the dataset and should not automatically be interpreted as the number of customer orders.

## Project Structure

```text
Swiggy-Data-Analysis-Excel/
│
├── README.md
├── Swiggy_Data_Analysis.xlsx
└── images/
