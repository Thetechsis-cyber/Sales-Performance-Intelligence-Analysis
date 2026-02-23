# 📊 Sales Performance Intelligence Dashboard
A Data-Driven Business Analysis Project*

## 1️⃣ Executive Summary

This project delivers an interactive dashboard built to analyze revenue growth, customer behavior, product performance, and geographic concentration across multiple years
(2011–2014).

The dashboard transforms raw transactional data into strategic insights by:

* Tracking Year-over-Year performance
* Identifying revenue concentration risks
* Evaluating discount impact on sales
* Highlighting high-performing customer segments and regions
* Enabling time-based performance analysis

The outcome: Clear, measurable insights that support revenue optimization and expansion strategy.

## 2️⃣ Business Context

### 🏢 Industry Scenario

A retail company operating across multiple U.S. states needed visibility into:

* Revenue trends
* Regional sales concentration
* Customer segment profitability
* Discount strategy effectiveness

Management lacked a centralized reporting system and relied heavily on static spreadsheets.

## 3️⃣ Business Problem

The organization faced three major challenges:

1. Revenue visibility gap – No dynamic way to track growth year-over-year.
2. Geographic concentration risk – Revenue potentially over-dependent on few states.
3. Discount strategy uncertainty – No clarity on how discounts affected performance.
4. Lack of segment-level insights – Customer behavior not fully understood.

Without structured analytics, strategic decisions were reactive rather than data-driven.

## 4️⃣ Project Objectives

The goal of this project was to:

* Build a centralized performance dashboard
* Implement time intelligence for YoY analysis
* Identify revenue concentration patterns
* Analyze customer and product contributions
* Deliver actionable business recommendations

## 5️⃣ Data Preparation & Modeling

### 🔎 Data Quality Checks

The following validation steps were performed:

* Verified absence of duplicate records
* Confirmed no missing values
* Validated data types:

  * Date columns → Date format
  * Revenue → Decimal/Numeric
  * Quantity → Whole number
  * Discount → Decimal
* Ensured categorical consistency (States, Regions, Segments)

### 📅 Calendar Table (Time Intelligence Foundation)

A dedicated Calendar Table was created to enable:

* Year-based filtering
* Quarter and Month analysis
* Year-over-Year comparisons
* Monthly trend analysis

The Calendar table was linked via the Order Date column to establish a proper star schema relationship.

## 6️⃣ Data Model Design

The model follows a simplified star schema structure:

Fact Table:

* Sales Transactions

Dimension Tables:

* Calendar

This structure enables scalable and efficient analytical querying.
<img width="581" height="379" alt="salesdiagram" src="https://github.com/user-attachments/assets/e987dca4-aefa-4ad1-a63b-08dc11f61580" />

## 7️⃣ DAX Measures Implemented

### Core KPIs

* Total Revenue
* Total Quantity
* Total Orders
* Average Discount

### Time Intelligence KPIs

* Revenue YoY Growth %
* Orders YoY Growth %
* Quantity YoY Growth %
* Average Discount YoY %

These measures enable dynamic KPI tracking based on selected filters.
<img width="908" height="159" alt="Daxx" src="https://github.com/user-attachments/assets/178c9323-dc13-4095-82a6-5543bd598a85" />


## 8️⃣ Dashboard Overview

### 🔹 KPI Summary Panel

Displays:

* Total Revenue: $2.30M
* Quantity Sold: 37,873
* Orders: 5,009
* Average Discount: 15.62%
* Year-over-Year performance indicators


## 9️⃣ Key Insights

1. Revenue Concentration Risk
   Over 50% of revenue comes from a few states.

2. Regional Dominance
   The West region leads overall revenue contribution with November($349.12k) having the highest sales

3. Strong Q4 Seasonality
   Revenue peaks consistently in Q4 months.

4. Consumer Segment Dominance
   Consumer segment($1.16m) drives the majority of sales.

5. Discount Sensitivity
   Discount levels require monitoring to ensure margin sustainability.

6. Technology Category Dominance
   Technoklog category($836.15k) drives the majority of sales.

## 🔟 Strategic Recommendations

### 1️⃣ Geographic Diversification Strategy

Expand targeted campaigns in underperforming regions (South & Central) to reduce dependency on top markets.

### 2️⃣ Seasonal Optimization

Leverage Q4 demand surge with:

* Inventory forecasting
* Strategic marketing spend
* Promotional campaigns

### 3️⃣ Discount Efficiency Analysis

Conduct margin analysis to:

* Identify optimal discount thresholds
* Prevent revenue leakage

### 4️⃣ Customer Retention Strategy

Focus on:

* Consumer loyalty programs
* Upselling high-performing categories

### 5️⃣ Category Growth Strategy

Analyze cross-selling opportunities between Office Supplies and Technology segments.

## 📈 Business Impact Potential

If implemented, insights from this dashboard could:

* Reduce geographic revenue risk
* Improve strategic allocation of marketing resources
* Optimize discount strategy
* Enhance forecasting accuracy
* Increase long-term revenue stability

## 🛠 Tools & Technologies

* Excel
* DAX
* Data Modeling (Star Schema)
* Time Intelligence Functions
* KPI Design & Business Analytics

## 📌 What This Project Demonstrates

✔ Data Cleaning & Validation

✔ Data Modeling & Relationships

✔ Advanced DAX Calculations

✔ Time Intelligence Implementation

✔ Business Problem Translation

✔ Insight Generation

✔ Strategic Recommendation Development

This project showcases the ability to move beyond dashboard creation into structured business analytics and strategic thinking.


## 🏁 Conclusion

This Sales Performance Intelligence Dashboard transforms transactional sales data into actionable business strategy.

The analysis highlights both strengths (strong regional markets and Q4 growth) and risks (geographic concentration and discount dependency).

By combining structured modeling, time intelligence, and KPI tracking, this project demonstrates end-to-end analytical capability — from raw data validation to
executive-level insight delivery.

