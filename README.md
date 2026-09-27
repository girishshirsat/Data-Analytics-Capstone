# Data-Analytics-Capstone
Capstone Project Tailwind Traders Sales, Profit Reports &amp; Dashboards.

# Tailwind Traders BI Capstone Project
 
## Overview
This project was completed as the Capstone for the **Microsoft Power BI Data Analyst Professional Certificate** on Coursera. It simulates a real-world business intelligence workflow for a fictional retail company, **Tailwind Traders**, covering the full analytics lifecycle: data preparation, data modeling, DAX-based aggregation, report building, and executive dashboarding with alerts and subscriptions.
 
## Objective
To help Tailwind Traders transform raw sales, purchase, and currency data into an interactive, decision-ready reporting solution that tracks revenue, profit, and operational KPIs — accessible both on desktop and mobile.
 
## Tools & Technologies
- Microsoft Excel (data preparation, formulas)
- Power BI Desktop (Power Query, Data Modeling, DAX)
- Power BI Service (dashboards, alerts, subscriptions)
- Python (used as a Power BI data source for exchange rate data)
- DAX (time intelligence & aggregation measures)
## Project Structure
 
### Phase 1: Data Preparation & Modeling
- **Excel data prep:** Calculated Cost per Unit, Gross Revenue, Total Tax, Net Revenue, and Profit for each sales record.
- **Data sourcing:** Loaded and cleaned four data sources in Power Query — Sales, Purchases, Countries, and Historical Currency Exchange (via Python script) — with correct data types and quality checks (Column Quality, Distribution, Profile).
- **Data modeling:** Built relationships between tables (Sales, Purchases, Countries, Exchange Data, Calendar) with appropriate cardinality (1:1, many-to-one) and cross-filter directions, following star-schema principles. Created a custom **Calendar table** and a calculated **Sales in USD** table for currency-normalized analysis.
### Phase 2: Aggregations & Reporting
- **DAX measures:** Built Yearly, Quarterly, and Year-to-Date Profit Margin measures using `DIVIDE`, `CALCULATE`, `DATESQTD`, and `TOTALYTD`, plus a `MEDIAN` measure for typical sales performance.
- **Performance testing:** Used the Performance Analyzer to validate DAX query load times (<200ms).
- **Sales Overview report:** Bar chart (Loyalty Points by Country), column chart (Quantity Sold by Product), pie chart (Median Sales Distribution by Country), line chart (Median Sales Over Time), KPI cards, and a country slicer — styled with the Accessible City Park theme.
- **Profit Overview report:** Bar chart (Net Revenue by Product), donut chart (Yearly Profit Margin by Country), area chart (Yearly Profit Margin Over Time), KPI cards, and a date slicer.
### Phase 3: Executive Dashboard & Alerts
- **Executive Dashboard:** Pinned key visuals from both reports into a single "Tailwind Traders Executive Dashboard" in Power BI Service, with a custom mobile layout prioritizing critical KPIs.
- **Alerts:** Configured a daily alert to flag when Gross Revenue USD drops below $400.
- **Subscriptions:** Set up weekly automated email subscriptions for the Sales Overview (Mondays, 5 AM) and Profit Overview (Mon/Wed/Fri, 6 AM) reports.
## Key Insights
- The UK led all countries in loyalty points (315).
- The **Modular Sofa Set** generated the highest Net Revenue at **$928.36 USD**.
- The UAE recorded the highest Median Sales value at **$680.79 USD**.
- Order ID 1035 (Amelia Carter) had a Net Revenue of $682.62 USD after currency conversion.
## Skills Demonstrated
- Data cleaning & business logic in Excel
- ETL and data transformation in Power Query
- Relational data modeling (star schema, cardinality, cross-filtering)
- DAX for time intelligence and KPI calculation
- Data visualization and report design in Power BI
- Dashboard creation, alerting, and automated reporting in Power BI Service
## Outcome
The final deliverable is a fully functional, interactive BI solution that enables Tailwind Traders' stakeholders to monitor sales and profit performance in real time, receive automated alerts on revenue thresholds, and access insights on both desktop and mobile devices — without needing to manually open Power BI.
 
