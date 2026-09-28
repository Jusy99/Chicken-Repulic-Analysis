# Chicken-Repulic-Analysis
# Analyzing Sales Performance and Profitability of a Nigerian Fast-Food Business

## 1. Project Overview

This project analyzes sales transactions from the Chicken Republic Lagos Sales Dataset to understand business performance, profitability, product contribution, location performance, and sales trends over time.

Using Microsoft Excel and Power BI, I cleaned and validated the dataset, performed exploratory data analysis, developed key performance indicators (KPIs), and built an interactive four-page dashboard.

The analysis covered 500 transactions from January 1 to June 21, 2024, generating approximately ₦3.95 million in revenue and ₦685.7 thousand in profit.

The goal was to transform raw transaction data into actionable insights that could support data-driven business decisions.

## 2. Business Problem

Raw sales records do not always provide a clear understanding of which products, categories, locations, and periods contribute most to business performance.

The business needs to understand its revenue and profitability patterns, identify high-performing products and locations, and investigate areas with relatively weaker performance.

This project addresses these needs by analyzing transaction-level data and presenting the findings through an interactive Power BI dashboard.

## 3. Research Questions

The analysis was designed to answer the following questions:

1. How do revenue and profit change over time?
2. Which products and categories generate the highest revenue?
3. Which products and categories generate the highest profit and profitability?
4. Which locations contribute the most to revenue and profit?
5. Are the highest-selling products also the most profitable?
6. Which products or locations show relatively weaker sales or profitability?
7. Which days of the week generate the highest sales?
8. How does business performance vary across locations and months?

## 4. Tools Used

* **Microsoft Excel:** Data cleaning, validation, exploratory data analysis, PivotTables, and initial KPI calculations.
* **Microsoft Power BI:** Data modeling, DAX measures, interactive visualizations, and dashboard development.
* **DAX:** Calculation of business performance metrics in Power BI.

## 5. Data Cleaning and Preparation

The dataset was prepared in Excel before being imported into Power BI.

The following steps were completed:

* Checked for missing values.
* Checked for duplicate records.
* Verified data types and date formatting.
* Checked consistency in product, category, and location values.
* Validated total sales using Quantity Sold × Unit Price.
* Reviewed profit values for anomalies.
* Created helper columns for Day of Week, Month, and Month Number.
* Used PivotTables to explore sales and profitability.

### Data Quality Summary

* Total transactions: 500
* Missing values: 0
* Exact duplicate rows: 0
* Analysis period: January 1 – June 21, 2024

## 6. Key Performance Indicators (KPIs)

The following KPIs were developed to measure overall performance.

| KPI                       |        Result |
| ------------------------- | ------------: |
| Total Revenue             | ₦3,946,443.80 |
| Total Profit              |   ₦685,697.17 |
| Total Units Sold          |         2,703 |
| Total Transactions        |           500 |
| Average Transaction Value |     ₦7,892.89 |
| Profit Margin             |         17.4% |

The profit margin was calculated as total profit divided by total revenue.

## 7. Power BI Dashboard

The interactive dashboard consists of four pages.

### Page 1: Executive Overview

Provides a summary of business performance through KPI cards, a monthly revenue trend, revenue by category, and revenue by location.

### Page 2: Product and Profitability

Examines product-level performance using revenue and profit comparisons, top products by profit, units sold by product, category profit margins, and a detailed product performance table.

### Page 3: Location and Time Analysis

Compares revenue and profit across locations, examines monthly performance and day-of-week sales patterns, and provides a location performance table and location-by-month revenue matrix.

### Page 4: Key Insights and Recommendations

Summarizes the major findings and presents recommendations for further investigation into product performance, location differences, and sales patterns.

## 8. Key Results and Insights

### Overall Performance

The business generated ₦3.95 million in revenue and ₦685.7 thousand in profit across 500 transactions, with an overall profit margin of approximately 17.4%.

### Product Performance

* **Ice Cream** was the leading individual product, generating ₦554,595.56 in revenue and ₦93,196.55 in profit.
* **Cake Slice** ranked second, generating ₦463,449.43 in revenue and ₦81,540.73 in profit.
* Ice Cream also recorded the highest unit sales, with 351 units.
* **Refuel Max** recorded the lowest revenue and profit among the products analyzed.

### Category Performance

* **Desserts** generated the highest category revenue at approximately ₦1.02 million and the highest category profit at approximately ₦174.7 thousand.
* **Meals** recorded the highest unit sales, with 712 units.
* **Snacks** generated approximately ₦174.4 thousand in profit, nearly matching Desserts despite lower unit sales.
* **Drinks** recorded the lowest revenue and profit among the four categories.

### Location Performance

* **Victoria Island** recorded the highest revenue at ₦775,312.47 and the highest profit at ₦137,070.65.
* **Yaba** recorded the lowest revenue at ₦544,684.34 and the lowest profit at ₦89,377.83.
* **Lekki** recorded the highest unit sales, with 521 units.
* **Surulere** recorded the highest transaction count, with 94 transactions.

### Time-Based Performance

* **April** was the strongest complete month, generating ₦836,012.88 in revenue and ₦143,610.67 in profit.
* Revenue increased from January through April before declining in May.
* **Thursday** recorded the highest revenue among the days of the week, at ₦638,963.56, followed by Friday at ₦625,719.81.

### Key Observation

Sales volume, revenue, and profit do not always produce identical rankings across products, categories, and locations. Examining these measures together provides a more complete picture of business performance.

## 9. Recommendations

Based on the findings, the following actions could be considered:

1. **Monitor high-performing products:** Track the availability and demand for Ice Cream and Cake Slice to help sustain their contribution to revenue and profit.
2. **Investigate lower-performing products:** Examine customer demand, pricing, and product placement for Refuel Max before making decisions about its future.
3. **Investigate location differences:** Examine operational factors, customer traffic, and product mix that may help explain why Yaba recorded lower revenue and profit than other locations.
4. **Analyze product performance by location:** Identify products that perform particularly well or poorly at individual locations to support inventory planning.
5. **Examine day-of-week patterns:** Investigate whether Thursday and Friday sales patterns persist over a longer period before using them to guide staffing or promotional decisions.

These are proposed actions based on the observed patterns, not outcomes already achieved by the business.

## 10. Limitations and Further Analysis

The dataset covers only part of 2024, limiting conclusions about annual trends and seasonality.

June contains data only from June 1 to June 21. Therefore, its totals should not be compared directly with those of the full preceding months.

The available data also does not establish why certain products or locations performed differently. Further analysis could incorporate customer demographics, operating costs, inventory levels, promotions, and customer traffic.

Potential next steps include product-by-location analysis, average transaction value comparisons across locations, and deeper investigation of the factors associated with profitability.

## 11. Conclusion

This project demonstrates how Excel and Power BI can be used to transform raw sales data into meaningful business insights.

Through data cleaning, exploratory analysis, KPI development, and interactive visualization, the project identified key patterns in product, category, location, and time-based performance.

The resulting dashboard provides a structured view of business performance and highlights areas where further investigation could support better-informed operational and sales decisions.

## 12. Dataset Source

**Dataset:** [Chicken Republic Lagos Sales Dataset – Kaggle](https://www.kaggle.com/datasets/olagokeblissman/chicken-republic-lagos-sales-dataset)

**Analysis period:** January 1 – June 
21, 2024.

---
*Project developed by Emelokwu Justin Ozioma | Tools: Microsoft Excel and Power BI*
une 2024, with June containing data through June 21. Therefore, longer-term trends and seasonal conclusions would require a larger and more complete dataset.
