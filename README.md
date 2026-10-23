# Tailwind Traders \| Retail Sales & Profitability Analytics

**End-to-End Business Intelligence Capstone**\
*Microsoft Power BI Data Analyst Professional Certificate --- Coursera*

Transforming retail sales, purchasing, and currency data into
interactive business insights using **Excel, Power Query, Python, DAX,
and Power BI**.

## Project Overview

Tailwind Traders is a fictional retail business used in the Microsoft
Power BI Data Analyst Professional Certificate on Coursera. This
capstone project demonstrates an end-to-end business intelligence
workflow, from data preparation and modeling to KPI development,
interactive reporting, and executive dashboard delivery.

The objective was to build a reporting solution that helps stakeholders
explore product performance, compare country-level metrics, monitor
revenue and profitability, and investigate changes over time.

-   **Project type:** Business Intelligence & Data Analytics
-   **Domain:** Retail & Sales Analytics
-   **Tools:** Microsoft Excel, Power Query, Power BI Desktop, Power BI
    Service, Python, DAX
-   **Reporting period:** 2020--2023

## Dashboard Previews

### 1. Sales Overview --- Product & Customer Performance

![Tailwind Traders Sales Overview](images/sales-overview.png)

**What this report explores** - Loyalty points across countries. -
Quantity purchased by product. - Median sales distribution by country. -
Median sales trends over time. - KPI summaries and interactive country
filtering.

**Key findings** - The UK recorded the highest displayed total loyalty
points, at **315**, followed by the USA at 305. - The UAE had the
highest displayed median sales value, approximately **\$680.79**. -
Product quantities in the displayed chart ranged from 1 to 6 units.

**Business application:** These comparisons can help stakeholders
investigate differences in customer engagement, product demand, and
sales performance across markets.

### 2. Profit Overview --- Revenue & Profitability

![Tailwind Traders Profit Overview](images/profit-overview.png)

**What this report explores** - Net revenue by product. - Yearly profit
margin by country. - Profit margin trends over time. - Year-to-date
profit margin. - Date-based filtering for historical analysis.

**Key findings** - The Modular Sofa Set generated the highest displayed
net revenue among the products shown, approximately **\$928.36**. - The
report displayed a total Net Revenue USD KPI of approximately
**\$9.83K**. - The Year-to-Date Profit Margin KPI displayed
**62.27%**. - The profit-margin trend included sharp declines that
warrant further investigation.

**Business application:** Stakeholders can identify revenue-leading
products, compare country-level margin metrics, and investigate unusual
changes before making pricing, cost-control, or inventory decisions.

*Note: These are observations from the displayed report. Additional
transaction, cost, and measure-level validation is required before
drawing conclusions about overall profitability.*

## Business Problem

Retail businesses need to combine sales, purchasing, geographic, and
currency data to understand business performance. Raw datasets alone do
not always provide an accessible view of key metrics or make it easy to
investigate changes over time.

This project addresses that challenge by building a consolidated BI
reporting solution that supports:

-   Monitoring key sales and profitability indicators.
-   Comparing products and countries.
-   Analyzing historical performance.
-   Exploring data through interactive filters.
-   Delivering recurring reports and threshold-based alerts through
    Power BI Service.

## Technical Implementation

### Phase 1 --- Data Preparation & ETL

**Tools:** Excel, Power Query, Python

-   Prepared sales records in Excel, including calculations for cost per
    unit, gross revenue, total tax, net revenue, and profit.
-   Imported and transformed Sales, Purchases, Countries, and Historical
    Currency Exchange data.
-   Used a Python script as a data source for historical exchange-rate
    information.
-   Applied appropriate data types and performed data-quality checks
    using column quality, distribution, and profiling.
-   Prepared currency-normalized data for USD-based reporting.

### Phase 2 --- Data Modeling & DAX

**Tools:** Power BI Desktop, DAX

-   Built relationships across Sales, Purchases, Countries, Exchange
    Data, and Calendar tables.
-   Applied appropriate relationship cardinality and cross-filter
    directions.
-   Created a custom Calendar table to support date-based analysis.
-   Built a calculated Sales in USD table for currency-normalized
    reporting.
-   Developed measures for median sales, yearly profit margin, quarterly
    profit, and year-to-date calculations.
-   Used functions including `DIVIDE`, `CALCULATE`, `DATESQTD`,
    `TOTALYTD`, and `MEDIAN`.
-   Used Performance Analyzer to inspect report visual performance and
    DAX query execution times.

### Phase 3 --- Report Development

**Tools:** Power BI Desktop

Developed two interactive report pages:

  Sales Overview                  Profit Overview
  ------------------------------- ---------------------------------
  Loyalty points by country       Net revenue by product
  Quantity purchased by product   Yearly profit margin by country
  Median sales by country         Profit margin over time
  Median sales over time          YTD profit margin KPI
  Country slicer                  Date slicer

Applied the Accessible City Park theme and selected visual types to
support comparisons, distributions, and time-series analysis.

### Phase 4 --- Power BI Service & Executive Reporting

**Tools:** Power BI Service

-   Published the reports to Power BI Service.
-   Created a consolidated **Tailwind Traders Executive Dashboard** by
    pinning selected visuals.
-   Designed a custom mobile layout to prioritize key metrics.
-   Configured a daily alert for Gross Revenue USD falling below
    **\$400**.
-   Set up weekly email subscriptions for the Sales Overview and Profit
    Overview reports.

These features demonstrate how a BI report can support recurring
monitoring and stakeholder access beyond the Power BI Desktop
environment.

## Business Insights & Recommendations

  -----------------------------------------------------------------------
  Observation                         Potential business action
  ----------------------------------- -----------------------------------
  The UK leads the displayed          Compare points per customer, repeat
  loyalty-points totals.              purchases, and retention across
                                      markets.

  The UAE has the highest displayed   Investigate transaction values,
  median sales value.                 customer segments, and product mix.

  The Modular Sofa Set leads the      Compare its profit margin and
  visible product revenue ranking.    demand before adjusting inventory.

  Profit margin has several sharp     Drill into the affected dates,
  declines over time.                 costs, discounts, and transaction
                                      records.
  -----------------------------------------------------------------------

These recommendations illustrate how dashboard findings can lead to
further analysis. The visuals alone do not establish the underlying
causes.

## Technology Stack

-   **Excel:** Initial data preparation and business calculations.
-   **Power Query:** ETL, data cleaning, transformation, and quality
    checks.
-   **Power BI Desktop:** Data modeling, DAX, report development, and
    visualization.
-   **DAX:** KPI measures, aggregations, and time intelligence.
-   **Python:** Historical currency exchange data sourcing.
-   **Power BI Service:** Executive dashboard, mobile layout, alerts,
    and email subscriptions.

## Skills Demonstrated

-   Data cleaning and transformation.
-   Exploratory data analysis and KPI definition.
-   Relational data modeling and star-schema concepts.
-   DAX measures and time-intelligence calculations.
-   Data visualization and dashboard design.
-   Currency normalization for financial reporting.
-   Performance Analyzer and report optimization.
-   Automated reporting workflows in Power BI Service.
-   Business interpretation and insight communication.


## Limitations & Future Improvements

-   Add a revenue-versus-profit comparison to distinguish sales
    performance from profitability.
-   Validate margin calculations and investigate unusual trend points.
-   Add transaction-level drill-through and product profitability
    analysis.
-   Improve metric definitions and documentation.
-   Explore additional customer-retention and inventory-performance
    measures.

## Project Outcome

This capstone demonstrates an end-to-end BI workflow: preparing data,
building a relational model, developing DAX measures, creating
interactive reports, and configuring dashboard delivery in Power BI
Service.

The result is a retail analytics solution designed to make key metrics
easier to explore and to support data-informed business discussions.

## Learning & Attribution

Completed as part of the **Microsoft Power BI Data Analyst Professional
Certificate on Coursera**.

This is an educational capstone using the fictional Tailwind Traders
business scenario. The findings and recommendations are based on the
project dataset and report visuals.

------------------------------------------------------------------------

**Author:** Girish Shirsath\
**GitHub:** [github.com/girishshirsat](https://github.com/girishshirsat)
