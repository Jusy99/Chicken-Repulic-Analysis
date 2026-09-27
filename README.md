# Chicken-Repulic-Analysis
# Analyzing Sales Performance and Profitability of a Nigerian Fast-Food Business

## Project Overview

This project analyzes 500 sales transactions from a Nigerian fast-food business between January and June 2024. The analysis was designed to understand sales performance, profitability, product performance, location performance, and sales trends over time.

Using Excel and Power BI, I cleaned and validated the dataset, performed exploratory analysis, developed key performance indicators, and built an interactive four-page dashboard.

The analysis generated ₦3.95 million in revenue and ₦685.7 thousand in profit across 500 transactions, with an overall profit margin of approximately 17.4%.

The goal was to transform raw transaction data into actionable business insights that could support decisions around products, locations, and sales performance.


## Business Problem

The business has transaction-level sales data, but raw sales records alone do not provide a clear view of which products, categories, locations, and periods are driving revenue and profitability.

The key business challenge is to transform the sales data into meaningful insights that can help identify strong-performing products and locations, understand sales trends, and highlight areas that may require further investigation.

This analysis therefore focuses on understanding overall sales and profit performance and identifying patterns that can support data-driven business decisions.


## Research Questions

The analysis seeks to answer the following questions:

1. How do revenue and profit change over time?

2. Which products and categories generate the highest revenue?

3. Which products and categories generate the highest profit and profitability?

4. Which locations contribute the most to revenue and profit?

5. Are the highest-selling products also the most profitable?

6. Which products or locations show relatively weaker sales or profitability and may require further investigation?

7. Which days of the week generate the highest sales?

8. Are there noticeable differences in performance across locations and months?
   

## Tools & Methodology

### Tools Used

* **Microsoft Excel** — Data cleaning, validation, exploratory analysis, PivotTables, and initial KPI calculations.
* **Power BI** — Data modeling, DAX calculations, interactive visualizations, and dashboard development.

### Methodology

#### 1. Data Cleaning & Validation

The dataset was reviewed and prepared in Excel before visualization. The cleaning process included:

* Checking for missing values
* Checking for duplicate transactions
* Validating data types
* Checking categorical consistency across locations, categories, and products
* Validating sales calculations using Quantity Sold × Unit Price
* Checking profit values for anomalies
* Creating helper fields for Day of Week, Month, and Month Number

The dataset contained **500 transactions** with no missing values or exact duplicate rows.

#### 2. Exploratory Data Analysis

PivotTables were used to analyze:

* Revenue and profit by category
* Revenue and profit by product
* Revenue and profit by location
* Monthly revenue and profit
* Sales performance by day of the week

This helped identify the major performance patterns before building the Power BI dashboard.

#### 3. KPI Development

The following KPIs were calculated:

* Total Revenue
* Total Profit
* Total Units Sold
* Total Transactions
* Average Transaction Value
* Profit Margin %

#### 4. Power BI Dashboard Development

The cleaned dataset was imported into Power BI, where DAX measures were created for the core KPIs.

The final dashboard consists of four pages:

1. **Executive Overview** — Overall business performance and headline KPIs.
2. **Product & Profitability** — Product revenue, profit, units, and category margins.
3. **Location & Time Analysis** — Location performance, monthly trends, and day-of-week patterns.
4. **Key Insights & Recommendations** — Main findings and areas for further investigation.

The dashboard was designed to allow users to explore the business from overall performance down to product, location, and time-level details.


## Key Results & Insights

### Overall Performance

During the analysis period, the business recorded:

* **Total Revenue:** ₦3,946,443.80
* **Total Profit:** ₦685,697.17
* **Total Units Sold:** 2,703
* **Total Transactions:** 500
* **Average Transaction Value:** ₦7,892.89
* **Profit Margin:** 17.4%

### Product Performance

* **Ice Cream** was the highest-performing product, generating ₦554,595.56 in revenue and ₦93,196.55 in profit.
* **Cake Slice** ranked second, generating ₦463,449.43 in revenue and ₦81,540.73 in profit.
* Ice Cream also recorded the highest unit sales with **351 units**.
* **Refuel Max** recorded the lowest revenue and profit among the products analyzed, with ₦143,345.22 in revenue and ₦25,014.92 in profit.

### Category Performance

* **Desserts** generated the highest category revenue at approximately ₦1.02 million and the highest category profit at approximately ₦174.7 thousand.
* **Meals** recorded the highest unit sales with 712 units.
* **Snacks** generated approximately ₦174.4 thousand in profit despite having fewer unit sales than Meals and Desserts.
* **Drinks** recorded the lowest revenue and profit among the four categories.

### Location Performance

* **Victoria Island** recorded the highest revenue at ₦775,312.47 and the highest profit at ₦137,070.65.
* **Yaba** recorded the lowest revenue at ₦544,684.34 and the lowest profit at ₦89,377.83.
* **Lekki** recorded the highest unit sales with 521 units.
* **Surulere** recorded the highest number of transactions with 94.

### Time-Based Performance

* **April** was the strongest complete month, generating ₦836,012.88 in revenue and ₦143,610.67 in profit.
* Revenue increased from January through April before declining in May.
* **Thursday** recorded the highest revenue among the days of the week at ₦638,963.56, followed by Friday at ₦625,719.81.
* June recorded the lowest monthly revenue and profit, but the dataset only covers **June 1–21**, so it should not be directly compared with the complete preceding months.

### Key Business Observations

The analysis shows that product, location, and time all contribute to differences in business performance. High sales volume does not always correspond directly to the same ranking in profitability, highlighting the importance of analyzing both revenue and profit when evaluating performance.

The results also identify specific areas for further investigation, particularly lower-performing locations and products, while highlighting high-performing products and locations that contribute significantly to overall business performance.


## Recommendations

Based on the analysis, the following areas could be considered by the business:

### 1. Monitor High-Performing Products

Products such as Ice Cream and Cake Slice made significant contributions to revenue and profit. Their availability, demand patterns, and sales performance should be monitored closely.

### 2. Investigate Lower-Performing Products

Refuel Max recorded the lowest revenue and profit among the products analyzed. Further analysis could examine customer demand, pricing, product placement, and sales frequency before making any decisions about the product.

### 3. Investigate Location Performance

Victoria Island recorded the highest revenue and profit, while Yaba recorded the lowest. Additional operational and customer data could be analyzed to understand the factors contributing to these differences.

### 4. Analyze Product Performance by Location

A deeper product-by-location analysis could reveal whether certain products perform particularly well in specific locations and help inform inventory and sales strategies.

### 5. Examine Sales Patterns Over Time

Thursday and Friday recorded the highest daily revenue in the dataset. Further analysis could determine whether these patterns are consistent over a longer period before using them to guide staffing or promotional decisions.

## Conclusion

This project demonstrates how transaction-level sales data can be transformed into actionable business insights using Excel and Power BI.

The analysis identified key differences in product, category, location, and time-based performance while providing a clear view of overall revenue and profitability.

The resulting four-page Power BI dashboard provides an interactive way to explore these patterns and supports further investigation into areas such as product-location performance, customer behavior, and operational efficiency.

An important limitation is that the dataset only covers January to June 2024, with June containing data through June 21. Therefore, longer-term trends and seasonal conclusions would require a larger and more complete dataset.
