**E-Commerce Sales & Customer Behaviour Analytics**

**Project Overview**
The E-Commerce Sales & Customer Behaviour Analytics project is an interactive Power BI report designed to explore 
sales performance, product performance, customer behaviour, order health, and operational trends.
It brings key business metrics and supporting visuals together to help users identify patterns,
investigate performance differences, and make data-informed decisions.

Tool: Microsoft Power BI
Report pages: 7
Project type: Business Intelligence / Data Analytics

**Problem Statement**
E-commerce businesses need to understand which products and categories generate sales, how customer segments behave, 
which cities contribute to performance, and how order and return patterns affect business outcomes.
Looking at sales alone may not explain customer behaviour or operational issues.

This dashboard brings these areas into one report so users can compare sales and customer metrics, review product and 
geographic performance, examine customer ratings, and explore factors associated with returns and order health.
The findings can support decisions about product strategy, customer retention, service quality, and operational improvements.

**Dashboard Pages**

**1. E-Commerce**
The opening page provides an entry point to the report and its analysis sections.

**2. Executive E-Commerce Overview**
Provides a high-level view of business performance, including visuals such as:
- Sales by Brand
- Sales by Category
  
Use this page to review the overall sales mix and compare performance across product groupings.

**3. Product & Customer Analytics**
Explores product performance and customer acquisition patterns. Visuals include:
- Average Order Value by Segment
- Top 10 Products by Units Sold
- Sales by Category
- Sales by City
- Top 10 Products by Sales
- Customers vs Sales by Acquisition Channel
  
This page helps compare product demand, revenue contribution, geographic results, and customer acquisition channels.

**4. Customer Behaviour & Order Health**
Focuses on customer value, order behaviour, and the relationship between ratings and purchasing metrics. Visuals include:
- Top Customers by Lifetime Sales
- AOV vs Rating

Use these views to investigate high-value customers and examine how average order value varies with customer ratings.

**5. Sales Trends & Operations**
Examines operational and customer-experience patterns. Visuals include:
- Delivery Days vs Customer Rating
- Return Rate by Customer Segment
  
This page can help identify relationships worth investigating between delivery time, ratings, and return behaviour.
A relationship shown in a visual should not automatically be interpreted as proof of causation.

**6. Executive Decision View**
Brings together exploratory visuals for decision support, including:
- Sales Decomposition
- Return Decomposition
- Customer Distribution by City
- Customers vs AOV by Acquisition Channel
- Product Sales vs Rating
  
Use the decomposition visuals to break down results by available dimensions and
investigate potential contributors to sales or returns.

**7. Executive Final Dashboard**
Provides a consolidated executive view with visuals including:
- Sales by Category
- Sales by City
- Sales by Segment
- Rating vs Sales
- Orders by Order Status
- Sales by Year

This page is suited to a final review of sales mix, geography, customer segments, order status, and yearly performance.

**Tools and Techniques**

Power BI Desktop      : Report creation and interactive data visualization.

Power Query           : Data import, profiling, cleaning, and transformation where required.

Data modelling        : Relationships between the sales fact data and relevant dimension tables, 
                        where present in the supplied model.
                        
DAX                   : Measures and calculated logic for business metrics, where implemented in the report.

Interactive reporting : Report pages and visual interactions that support focused analysis.

**Suggested Analysis Workflow**

- Open the PBIX file in Power BI Desktop.
- Review the data model and confirm that relationships between tables are appropriate.
- In Power Query, check column quality, distribution, data types, missing values, and duplicate records.
- Confirm that date, sales, order, customer, product, city, segment, rating, delivery,
  and return fields have suitable data types and meanings.
- Review the measures used by cards and charts, and verify their results against the source data.
- Use the report pages to move from executive-level results to product, customer, and operational analysis.
- Apply available slicers and visual filters to investigate specific periods, segments, cities,
  products, or other business dimensions.
- Validate any important finding against the underlying data before using it for a business decision.

**Key Business Questions**

The report is designed to help investigate questions such as:
1.  Which brands and categories contribute most to sales?
2.  Which products lead in units sold and sales value?
3.  How does average order value vary by customer segment?
4.  Which cities contribute to customer and sales activity?
5.  Which customers contribute the most lifetime sales?
6.  How do customers and average order value vary by acquisition channel?
7.  Is there a visible relationship between delivery days and customer ratings?
8.  How does return rate vary across customer segments?
9.  How do sales and ratings compare across products?
10. How are orders distributed by order status?
11. How does sales performance change by year?

**Main Insights and Recommendations**

The PBIX contains visuals intended to answer the questions above, but exact values and rankings
should be read from the report with the relevant filters applied. 

The following are areas to investigate, not claims that a specific result has already been proven:
Sales mix              : Compare sales by category and brand to identify major revenue contributors and 
                         categories that may need attention.
                         
Product performance    : Compare the top products by sales with the top products by units sold. 
                         High volume and high revenue are different measures and may lead to different decisions.
                         
Customer segments      : Review average order value and sales by segment to understand which groups contribute more value. 

Geographic performance : Compare sales and customer distribution by city to identify strong markets and 
                         locations that may warrant further investigation.
                         
Customer value         : Review top customers by lifetime sales to understand revenue concentration and 
                         consider suitable retention activities.
                         
Acquisition channels   : Compare customer counts, sales, and average order value by acquisition channel 
                         rather than relying on customer volume alone.
                         
Delivery experience    : Investigate delivery days alongside customer ratings. 
                         Check other factors before concluding that delivery time is the cause of a rating change.
                         
Returns                : Compare return rates by customer segment and use the return decomposition visual 
                         to investigate contributing categories or dimensions.
                         
Order health           : Review orders by status to identify unusual concentrations in pending, 
                         cancelled, returned, or other statuses available in the data.
                         
Trend monitoring       : Use sales by year to review longer-term changes, ensuring that date fields and 
                         time-period filtersare configured correctly.

**Recommended next steps**

- Validate the highest- and lowest-performing categories, products, and cities using the current report filters.
- Investigate segments with comparatively high return rates before proposing operational changes.
- Review customer ratings together with delivery and product measures to identify areas for further analysis.
- Set measurable business targets only after confirming the historical baseline and business requirements.
- Record the date range and filter selections whenever reporting KPI values, so comparisons remain consistent.

**How to Use the Dashboard**

- Open the relevant report page using the page navigation.
- Select a data point in a chart to cross-filter or highlight related visuals, where interactions are enabled.
- Use available slicers and filters to narrow the analysis.
- Hover over a visual to inspect tooltips and additional details.
- Clear filters when returning to an overall view.
- Check the filter context before copying KPI values into a presentation or report.

**Conclusion**

- The E-Commerce Sales & Customer Behaviour Analytics report combines 
executive reporting with product, customer, geographic, and operational analysis. 

- It provides a structured way to investigate sales drivers, customer value, ratings, order status, 
and returns, helping stakeholders move from summary metrics to more focused business questions.


**1. Overall business is generating strong sales**

₹202.84M Net Sales
from:
100,000 orders

**2. Sports is the biggest sales category**

Sports alone contributes almost 29% of total sales making it the primary revenue driver.

**3. Brand E is the strongest brand**

Brand E = ₹61.07M sales
It contributes approximately: 30.11% of total sales

Brand E is substantially ahead of the other brands.

**4. Bengaluru is the strongest city**

Bengaluru — ₹39.20M
It contributes approximately: 19.32% of total sales

The next largest markets are:
- Hyderabad — ₹31.57M
- Mumbai — ₹26.72M
- Pune — ₹26.65M

**5. Organic acquisition generates the most sales**

Organic contributes approximately 27.88% of total sales.

Invest in SEO, organic content and repeat/brand-driven acquisition 
because Organic is currently the largest revenue-generating channel.

**6. Regular customers dominate revenue**

Regular customers generate almost half of total sales.

However, the VIP segment has only 5.11% of sales, 
So there is an opportunity to convert Premium/Regular customers into higher-value VIP customers.

**7. Customer retention is extremely strong**

97.87% Repeat Customer Rate

There are approximately:
17,543 repeat customers out of 17,925 unique customers.
This is one of the strongest findings in the dataset.

Business recommendation:
Focus on:
- Loyalty programs
- Personalized offers
- VIP upgrades
- Cross-selling
- Repeat-purchase campaigns

**8. UPI is the leading payment method closely followed by credit card**

UPI — ₹62.95M
credit card - ₹55.28M

UPI represents the largest payment contribution.

**9. Returns and cancellations need attention**

Return Rate       : 6.83%
Cancellation Rate : 6.01%

**10. Product 32 is the top sales product**

Product 32  : ₹26.80M sales
However, Product 48 is the unit-volume leader with: 6,514 units

This creates an important distinction: Highest sales ≠ highest volume

**11. Sales slightly declined year-over-year****

  Year	Sales
- 2024	₹102.15M
- 2025	₹100.69M

Overall YoY change: −1.43%
So, although the business has a large sales base and excellent repeat-customer performance, 
revenue slightly declined in 2025

**12.Customer experience is relatively stable**

Average:
- Delivery: 4.53 days
- Rating: 3.96 / 5

----------------------------------------------------------------------------------------------------------------------------
                           Project: E-Commerce Sales & Customer Behaviour Analytics
                                     Platform: Microsoft Power BI
