# Maven Market: Retail Business Analytics and Optimization Report

**Welcome to my personal project repository!**

## Table of Contents
- [**Project Background**](#project-background)
- [**Project Assets**](#project-assets)
- [**Data Structure and Initial Checks**](#data-structure-and-initial-checks)
- [**Insights**](#insights)
- [**Recommendations**](#recommendations)

## Project Background
Maven Market, a fictional retail brand, started in the mid-1990s and offers a wide variety of consumer products. By 1998, it had expanded to Canada and Mexico, having previously been only in the USA. This expansion has allowed Maven Market to gather valuable sales, products, customers, and stores data, helping to shape its strategic directions. 

This project analyzes two years of data (1997–1998) to uncover insights that improve profitability, product offerings, customer satisfaction, and efficiency. The focus is on topline performance, product evaluation, customer trends, and operational metrics to guide business growth.

### Insights and Recommendations Focus:
The project highlights four key areas of improvement:

1. [Executive Summary](#executive-summary),
reviews overall performance, including revenue, order trends, and profit margins.

2. [Product Performance](#product-performance),
examines profit margins, sales targets, and product returns.

3. [Customer Behavior](#customer-behavior),
analyzes customer retention and acquisition trends over two years.

4. [Operational Efficiency](#operational-efficiency),
evaluates store performance and revenue per square foot across regions.


## Project Assets
To make the analysis and insights easy to explore, the following resources are available:

- The SQL queries with PostgreSQL for data preparation can be found [here](https://mramadhankesapi.github.io/Data-Preparation-Process__for__Maven-Market...Retail-Analytics-and-Optimization/).

- The DAX measures for data analysis and analysis questions can be found [here](https://mramadhankesapi.github.io/DAX-Measures__for__Maven-Market...Retail-Analytics-and-Optimization/).

- The Power BI dashboard can be downloaded here: [Maven Retail Analytics and Optimization.pdf](https://github.com/user-attachments/files/18759867/Maven.Retail.Analytics.and.Optimization.pdf) or [Maven Retail Analytics and Optimization.pbix](https://github.com/MRamadhanKesaPI/Maven-Market...Retail-Analytics-and-Optimization/blob/main/Maven%20Retail%20Analytics%20and%20Optimization.pbix).

**Note**: Due to issues with my Microsoft account, the  interactive Power BI content will be updated once technical issues with my Microsoft account are resolved.


## Data Structure and initial Checks
The Maven Market database contains seven tables: customers, products, stores, regions, calendar, returns, and orders, with a total of 289,511 rows.

![Maven Data Structure](https://github.com/user-attachments/assets/722ccc07-b46b-4e53-a5a3-292a64385ddf)

Before starting the analysis, thorough quality checks were done to prepare the data and get familiar with Maven Market's datasets. The SQL queries for data preparation can be found [here](https://mramadhankesapi.github.io/Data-Preparation-Process__for__Maven-Market...Retail-Analytics-and-Optimization/)


## Insights
### Executive Summary
Maven Market achieved strong financial results in 1998, with a $1.05M profit and a 59% profit margin, driven by expansion into Mexico and Canada. Revenue grew by 112% compared to the previous year, supported by strong product performance.

The USA remains the top revenue source, but Mexico’s rapid growth in just one year shows it could soon compete the USA. This highlights Mexico’s strong market potential and growing customer demand.

"Hermano" is the top-selling brand, contributing 3.21% of total sales, while "Plato" leads with the highest profit margin of 63.6%, showcasing operational efficiency despite lower revenue. These results set the stage for further analysis and growth opportunities.

A detailed overview of these insights is available in the Power BI dashboard, which can be downloaded here:  [Maven Retail Analytics and Optimization.pdf](https://github.com/user-attachments/files/18759867/Maven.Retail.Analytics.and.Optimization.pdf) or [Maven Retail Analytics and Optimization.pbix](https://github.com/MRamadhanKesaPI/Maven-Market...Retail-Analytics-and-Optimization/blob/main/Maven%20Retail%20Analytics%20and%20Optimization.pbix).

![EXE SUMMARY](https://github.com/user-attachments/assets/bd0dd2bb-cf1f-4b63-a099-699ba282fc71)


### Product Performance:
- "Best Choice" generates $42,738 in revenue with a 60.6% profit margin, showing consistent upward sales trends and strong performance.
- "Plato" and "BBB Best" have the highest profit margins (63.6% and 62.1%, respectively) but lower sales (~$30K). Adjusting prices slightly could boost sales while maintaining profitability.
  
**Note**: The report includes a drillthrough page in Power BI for detailed product insights. Selecting a product brand in any of the pages will updates this dashboard with specific brand selected.

![Product Detail 1](https://github.com/user-attachments/assets/07b44c5a-df9d-4794-b7ea-2e0b6f401ac1)

![Product Detail 2](https://github.com/user-attachments/assets/23782158-3def-4122-83f5-e00cc1dc2c29)


### Customer Behavior:
- Maven Market had 8,842 customers over two years, with 8,060 joining in 1998, indicating rapid growth that year.
- A 98.8% retention rate shows strong customer loyalty and satisfaction.
- Bronze membership generates the most revenue, particularly from lower and middle-income customers, offering an affordable option, better than having no membership at all (the "normal" status).

![Customer Behaviors](https://github.com/user-attachments/assets/430427b2-70be-4470-a048-4243dd164ed0)


### Operational Efficiency:
- USA stores achieve high revenue per square foot ($3.24) but have low order frequency (28), indicating fewer but higher-value purchases.
- Mexico shows higher order frequency (66) but lower revenue per square foot ($1.74), suggesting frequent smaller transactions.
- We focus on USA stores as they have been running for two years. Underperforming USA stores (e.g., Store 14, Store 2, Store 22) earn less than $0.50 per square foot, requiring further evaluation for improvement.

![Operational Efficiency](https://github.com/user-attachments/assets/467e5d00-ead8-4167-be73-1aa82c7cbe2f)


## Recommendations
**1. Adjust Pricing for High-Margin, Low-Sales Products:**
   - Slightly lower prices for products like Plato and BBB Best to boost sales while maintaining profit margins.
   - Test the strategy on other similar products if successful.

**2. Bundle or Reposition Low-Performing Products Outside Top 50:**
   - Bundle or reposition products generating under $10K in revenue to improve sales and inventory turnover.
   - Scale successful strategies to other underperforming items.
     
**3. Leverage Mexico's Growth Potential:**
   - Increase marketing and distribution efforts in Mexico to accelerate revenue growth.
   - Optimize product offerings to tap into its high demand and potential.
  
**4. Optimize Underperforming USA Stores:**
   - Investigate underperforming stores (e.g., Store 14, Store 2, Store 22) for operational issues.
   unlike stores in other countries, which have only been open for one year,
   - Consider reallocating resources or closures to improve profitability.

**5. Maximize Customer Retention and Upsell Membership Tiers:**
   - Enhance the Bronze membership program and create pathways for upgrades to higher tiers.
   - Leverage the 98.8% retention rate to maximize customer lifetime value.

### Thank you for exploring this project, Feel free to hear your thoughts, insights, or any feedback! Let’s keep the discussion going!


