# Maven Market: Retail Business Analytics and Optimization Report

## Project Background
Maven Market, established in the mid-1990s, is a fictional retail brand specializing in a diverse range of consumer products. Over the years, it has expanded operations across North America, including the United States, Canada, and Mexico. By 1997, Maven Market had gathered substantial sales, product, and customer data, yet these datasets were underutilized for strategic decision-making.

This project thoroughly analyzes two years of historical data (1997–1998) to uncover actionable insights that can drive profitability, optimize product offerings, improve customer satisfaction, and enhance operational efficiency. The analysis is centered around evaluating executive summary, product performance, customer behavior, and operational efficiency to provide recommendations for business improvement.

### Insights and Recommendations Focus:
The project explores and provides actionable insights across the following critical business dimensions:

1. [**Executive Summary**](#executive-summary),
evaluation of topline performance, including revenue trends, order volume, and profit margins.

2. [**Product Performance**](#product-performance),
assessment of profit margins, product sales targets, and the impact of returns.

3. [**Customer Behavior**](#customer-behavior),
analysis of customer retention and acquisition patterns over two years.

4. [**Operational Efficiency**](#operational-efficiency),
store performance evaluation by country and revenue per square foot.


## Project Assets
To make the analysis and insights easy to explore, the following resources are available:

- The SQL queries for data preparation can be found [here](https://mramadhankesapi.github.io/Supporting-SQL-Queries-for-Retail-Analytics-and-Optimization_Maven-Market-Case-Study/)

- The DAX measures for exploratory data analysis (EDA) process, along with the corresponding analysis questions can be found [here](https://mramadhankesapi.github.io/Supporting-DAX-Measures-for-Retail-Analytics-and-Optimization_Maven-Market-Case-Study/)

- The Power BI dashboard in pdf format can be downloaded here: [Maven Market Dashboard.pdf](https://github.com/user-attachments/files/18228058/Maven.Market.Dashboard.pdf)

**Note**: Due to issues with my Microsoft account, the interactive Power BI content is not available in this portfolio. I will update it once the issue is fixed.


## Data Structure & initial Checks
Maven Market's database has seven tables: customers, products, stores, regions, calendar, returns, and orders, with a total of 289,511 rows across all tables.

![full_name](https://github.com/user-attachments/assets/5918f224-027c-44de-8bc9-a2f46f588e7a)

Before beginning the analysis, comprehensive quality checks were performed to ensure data preparation and to familiarize with Maven Market's datasets. The SQL queries for data preparation can be found [here](https://mramadhankesapi.github.io/Supporting-SQL-Queries-for-Retail-Analytics-and-Optimization_Maven-Market-Case-Study/)


## Executive Summary
### Overview of Finding
Maven Market has achieved strong financial results, with a $1.05M profit and a 59% profit margin, driven by rapid growth in 1998 from expanding into Mexico and Canada. Revenue has increased by 112% compared to last year, thanks to expansion and strong product performance.

The USA is still the top revenue source, but Mexico's rapid growth, despite only being operational for a year, shows it could soon compete with the USA. In just one year, Mexico has experienced significant market penetration, demonstrating a strong customer base and demand for Maven Market's offerings. 

Hermano is the top-selling brand, making up 3.21% of total sales, indicating high customer demand. Notably, Plato stands out with the highest profit margin of 63.6%, despite lower revenue, showing great operational efficiency. The next sections will look at key factors behind this performance and explore opportunities for growth.

Below is an overview from the Power BI dashboard, with additional examples provided throughout the report. The Power BI dashboard in pdf format can be downloaded here: [Maven Market Dashboard.pdf](https://github.com/user-attachments/files/18228058/Maven.Market.Dashboard.pdf)

![EXE SUMMARY](https://github.com/user-attachments/assets/bd0dd2bb-cf1f-4b63-a099-699ba282fc71)


### Product Performance:
- Best Choice balances strong profit margins and sales targets, with $42,738 in revenue and a 60.6% profit margin. It shows a steady upward sales trend, making it a strong performer with high sales and proportional profits.
- Plato and BBB Best have high profit margins (63.6% and 62.1%, respectively), but lower sales around $30K. However, while BBB Best shows a better sales trend, Plato missed its 10% target last month. Adjusting the price slightly for both products could help attract more buyers.

**Note**: This report includes a drillthrough page for detailed product performance analysis. By clicking on a product brand in any of the pages, the report will automatically navigate to the product performance page, updating with data specific to the selected product.

![Product Detail 1](https://github.com/user-attachments/assets/07b44c5a-df9d-4794-b7ea-2e0b6f401ac1)

![Product Detail 2](https://github.com/user-attachments/assets/23782158-3def-4122-83f5-e00cc1dc2c29)


### Customer Behavior:
- Maven Market has had a total of 8,842 customers over the past two years, with most of them (8,060) in 1998. This shows strong customer growth, especially in that year.
- Maven Market has a high 98.8% retention rate, meaning most customers keep coming back. This shows that customers are happy and loyal to the brand.
- Bronze membership brings in the most revenue, especially from lower and middle-income customers. These customers find the benefits of the bronze membership, which are likely more affordable, better than having no membership at all (the "normal" status).

![Customer Behaviors](https://github.com/user-attachments/assets/430427b2-70be-4470-a048-4243dd164ed0)


### Operational Efficiency:
- USA stores achieve high revenue per SQFT ($3.24) with a low order frequency (28), indicating fewer but higher-value purchases. In contrast, Mexico has a higher order frequency (66) but lower revenue per SQFT ($1.74), suggesting frequent but smaller transactions. The - - opportunity lies in boosting order frequency in the USA and Canada while increasing order values in Mexico to balance both performance metrics.
- We focus on USA stores as they have been running for two years. Stores like Store 14, Store 2, and Store 22 consistently underperform, earning under $0.50 revenue per square foot, highlighting the need for further evaluation.

![Operational Efficiency](https://github.com/user-attachments/assets/467e5d00-ead8-4167-be73-1aa82c7cbe2f)


### Recommendations:
1. Adjust Pricing for High-Margin, Low-Sales Products:
   - **Recommendation**: Slightly adjust prices for products like Plato and BBB Best to boost sales while maintaining strong profit margins. If this successful, apply to other similar products.
   - **Rationale**: These products have high profit margins but low sales. Small price adjustments or targeted promotions could drive more volume without compromising profitability.

2. Bundle or Reposition Low-Performing Products Outside Top 50:
   - **Recommendation**: Bundle or reposition products outside the top 50, especially those generating under $10k in revenue, to reduce inventory costs and boost sales.
   - **Rationale**: Products with low revenue can benefit from bundling or repositioning to improve sales and inventory turnover. Successful strategies with these low-revenue products can be scaled to other underperforming items.

3. Leverage Mexico's Growth Potential:
   - **Recommendation**: Increase marketing and distribution efforts in Mexico to capitalize on its rapid growth and close the gap with the USA in revenue.
   - **Rationale**: Despite being operational for only one year, Mexico's rapid growth indicates untapped potential. Expanding marketing efforts and optimizing product offerings can accelerate its revenue growth.
  
4. Optimize Underperforming USA Stores:
   - **Recommendation**: Investigate underperforming stores (e.g., Store 14, Store 2, Store 22) for operational issues and consider reallocation of resources or store closures.
   unlike stores in other countries, which have only been open for one year,
   - **Rationale**: These stores have been operating for two years, unlike stores in other countries, which have only been open for one year. Despite the longer operating time, these stores still underperform. Addressing operational issues or reallocating resources could improve their performance and profitability.

5. Maximize Customer Retention and Upsell Membership Tiers:
   - **Recommendation**: Enhance the Bronze membership program with additional benefits and create a pathway for customers to upgrade to higher tiers.
   - **Rationale**: With a 98.8% retention rate, focusing on increasing revenue from loyal customers through tiered memberships will maximize lifetime value.




