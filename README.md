# Swiggy Food Sales & Business Analytics Dashboard — Excel

## 📊 Project Overview

This project analyzes a Swiggy food-delivery dataset using Microsoft Excel to uncover sales patterns, restaurant performance, geographic trends, food-type contribution, and business drivers.

The objective was to move beyond basic reporting and use Excel to explore:

- What are the major sales trends?
- Which restaurants contribute the most to sales?
- How concentrated are sales among top restaurants?
- Is restaurant rating strongly associated with sales?
- How strongly is record volume associated with sales?
- Which food type contributes more to sales?
- Which states and cities contribute the most sales?
- Which restaurants have the highest average price per record?

---

## 🛠️ Tools & Techniques

- Microsoft Excel
- PivotTables
- PivotCharts
- Slicers
- Excel formulas
- Data aggregation
- KPI analysis
- Trend analysis
- Geographic analysis
- Correlation / linear relationship analysis
- Business-driver analysis
- Data visualization

---

## 📁 Dataset

The dataset contains food-delivery records covering **January 2025 to August 2025**.

### Dataset fields

- State
- City
- Order Date
- Day
- Quarter
- Week
- Restaurant Name
- Location
- Category
- Dish Name
- Food Type
- Price (INR)
- Rating
- Rating Count

The dataset contains approximately **197K records**.

---

## 📌 Key KPIs

| KPI | Value |
|---|---:|
| Total Sales | ₹53.01M |
| Average Rating | 4.34 |
| Total Rating Count | 5.59M |
| Total Records | 197.43K |
| Average Price per Record | ₹268.51 |

---

## 🔍 Key Insights

### 1. Top Restaurant Concentration

The top 10 restaurants contributed **34.16% of total sales**, while the top 5 contributed **25.39%**.

This indicates that a meaningful share of the dataset's sales is concentrated among a relatively small group of restaurants.

### 2. Restaurant Rating vs Sales

The linear relationship between restaurant rating and sales produced an **R² of 0.002**.

This suggests that restaurant rating alone has very limited explanatory power for sales in this dataset.

### 3. Record Count vs Sales

Record Count showed a very strong linear relationship with sales, with an **R² of 0.9762**.

This indicates that restaurants with more records in the dataset tend to have substantially higher sales.

This is an observed relationship in the dataset and should not be interpreted as causation.

### 4. Food Type Contribution

Vegetarian items accounted for approximately **64.5% of total sales**, compared with approximately 35.5% for non-vegetarian items.

### 5. Geographic Contribution

**Karnataka** was the highest-contributing state, accounting for approximately **10.29% of total sales**.

---

## 📈 Analysis Performed

### Sales Trends
- Monthly Sales Trend
- Quarterly Sales Analysis
- Weekly Sales Trend
- Sales by Day of Week

### Product & Food Analysis
- Sales by Food Type
- Restaurant-level sales analysis
- Average Price per Record

### Geographic Analysis
- Sales by State
- Top 5 States by Sales
- Top 5 Cities by Sales

### Business Driver Analysis
- Top 10 Restaurants by Sales
- Restaurant Rating vs Sales
- Record Count vs Sales
- Top Restaurants by Average Price per Record

### Interactive Analysis
The dashboard includes interactive slicers for:

- Month
- Category
- Restaurant Name

---

## 📊 Dashboard Preview

![Swiggy Excel Dashboard](images/dashboard.jpg)

---

## 💡 Business Takeaway

The analysis shows that sales performance in this dataset is more closely associated with record volume than with restaurant rating.

It also highlights significant sales concentration among leading restaurants and a strong contribution from vegetarian items.

The project helped me practice the process of moving from:

**Raw Data → Analysis → Insights → Business Storytelling**

---

## ⚠️ Data & Analysis Notes

- `Price (INR)` is used as the sales measure in this analysis.
- `Record Count` refers to the number of dataset records and should not automatically be interpreted as actual orders.
- `Average Price per Record` is calculated as Sales ÷ Record Count and should not be interpreted as true customer AOV or profitability.
- The relationship analyses show association within this dataset and do not establish causation.
- Q3 covers July–August only and represents a partial quarter.
- Week 36 represents a partial week and should not be compared directly with full weeks.

---

## 🎯 Project Objective

The main objective was to demonstrate how Microsoft Excel can be used not only for reporting, but also for structured business analysis and insight generation.

---

## 👤 Author

**Sharad Durgekar**

Data Analyst | Power BI | SQL | Python | Excel

---

## 🔗 Project Files

The complete Excel workbook used for the analysis is available in this repository.


```text
Swiggy-Data-Analysis-Excel/
│
├── README.md
├── Swiggy_Data_Analysis.xlsx
└── images/
