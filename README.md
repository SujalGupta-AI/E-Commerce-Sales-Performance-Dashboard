# E-Commerce Sales Performance Dashboard

![Main Dashboard Snapshot](Snapshot%20of%20The%20Dashboard.png)

## Executive Summary
This project features an E-Commerce Sales Dashboard built using Microsoft Excel to track and analyze annual sales and profitability. By aggregating transactional data and calculating Year-over-Year (YoY) performance (2016 vs. 2017), the dashboard provides a clear view of business growth. Overall, the business saw strong positive momentum, with total sales growing by over 20% and profits increasing by over 14% from 2016 to 2017. The analysis breaks down these high-level metrics across various product sub-categories and geographical regions to uncover specific drivers of growth.

## Business Problem
For a growing e-commerce platform, maintaining profitability while scaling revenue is a complex challenge. To make informed strategic decisions, the business needed a way to:
* **Track YoY Growth:** Understand how overall sales and profits compare to the previous year.
* **Evaluate Product Performance:** Identify which product sub-categories (e.g., Phones, Chairs, Machines, Binders) are driving revenue and which are lagging.
* **Geographic Optimization:** Pinpoint top-performing states and cities (e.g., New York City, Seattle vs. Los Angeles) to optimize regional marketing and distribution efforts.

## Methodology
1. **Data Ingestion & Backend Processing:** Raw sales data was structured in Excel. A dedicated "Backend Work" sheet was utilized to create Pivot Tables summarizing total Sales and Profits by Year, State, City, and Sub-Category.
2. **Metric Calculation:** Calculated custom Year-over-Year (`vs PY`) growth metrics for both Sales and Profits to establish a baseline for performance tracking. 
3. **Dashboard Construction:** Developed a "Dashboard" sheet that visually connects to the backend pivot tables. The layout allows stakeholders to easily compare 2016 and 2017 metrics side-by-side for Sub-Categories and top Cities.

## Skills
* **Tools:** Microsoft Excel 
* **Data Processing:** Pivot Tables, Data Aggregation, and Structuring (`Backend Work` tracking)
* **Data Analysis:** Financial Performance Tracking, Year-over-Year (YoY) Growth Calculation, Profitability Analysis
* **Data Visualization:** Excel Dashboarding

## Results & Business Recommendation

### Key Results
* **Overall Growth:** Total sales increased from **$609,205** in 2016 to **$733,215** in 2017, representing a **20.35%** YoY growth. Profit also grew from **$81,795** to **$93,439** (**14.23%** YoY).
* **Category Highlights:** * **Binders** and **Phones** were major drivers of growth, with Binders seeing a massive ~46.5% increase in sales.
  * Conversely, the **Machines** sub-category underperformed, experiencing a ~22.1% drop in sales compared to the previous year.
* **Geographic Trends:** * **New York City** and **Seattle** saw massive spikes in sales volume. (Seattle grew by over 252% YoY for select product segments).
  * **Los Angeles**, despite being a high-volume city, experienced a slight decline in sales (-13.3% YoY).

### Business Recommendations
1. **Investigate Underperforming Segments:** Conduct a deep dive into the "Machines" category and the Los Angeles market to identify why sales are contracting. Check for stockouts, pricing issues, or increased local competition.
2. **Capitalize on High-Growth Areas:** Allocate more marketing budget and inventory to highly profitable and rapidly growing categories like Phones and Binders. 
3. **Replicate Regional Success:** Analyze the marketing and operational strategies used in New York City and Seattle during 2017 and attempt to replicate them in underperforming or stagnant cities.
4. **Monitor Profit Margins:** Since sales grew at 20.35% but profit only grew at 14.23%, investigate costs of goods sold (COGS) and shipping expenses to ensure the business isn't sacrificing its profit margin for revenue growth.

## Next Step
* **Advanced BI Integration:** Migrate this Excel-based data model into a dedicated Business Intelligence tool like Power BI or Tableau for more interactive, drill-down capabilities.
* **Customer Level Analysis:** Incorporate customer demographic data and order IDs to analyze Customer Acquisition Cost (CAC) and Lifetime Value (LTV).
* **Time-Series Forecasting:** Implement monthly or quarterly trend tracking instead of purely annual comparisons to better capture seasonality in e-commerce purchasing behavior.
