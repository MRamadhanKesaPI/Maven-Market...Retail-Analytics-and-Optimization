# Intregated Business Analytics

## Project Background
Maven Market, established in the mid-1990s, is a fictional retail brand specializing in a diverse range of consumer products. Over the years, it has expanded operations across North America, including the United States, Canada, and Mexico. By 1997, Maven Market had gathered substantial sales, product, and customer data, yet these datasets were underutilized for strategic decision-making.

This project thoroughly analyzes two years of historical data (1997–1998) to uncover actionable insights that can drive profitability, optimize product offerings, improve customer satisfaction, and enhance operational efficiency. The analysis is centered around evaluating sales performance, product trends, customer behaviors, and store operations to provide recommendations for business improvement.

#### Insights and Recommendations Focus:
The project explores and provides actionable insights across the following critical business dimensions:

1. Sales Trends Analysis
Evaluation of topline performance, including revenue trends, order volume, and profit margins.

2. Product Performance
Assessment of profit margins, product sales targets, and the impact of returns.

3. Customer Behavior Analysis
Analysis of customer retention and acquisition patterns over two years.

4. Operational Efficiency
Store performance evaluation by country and revenue per square foot.


## Project Assets
To make the analysis and insights easy to exploe, the following resources are available:

- The SQL queries for data preparation can be found [here](https://mramadhankesapi.github.io/SQL-Queries-for-for-Rama-Kesa-Portfolio/)

- The DAX measures for exploratory data analysis (EDA) process, along with the corresponding analysis questions can be found [here](https://mramadhankesapi.github.io/DAX-Measures-for-Rama-Kesa-Portfolio/)

- Power BI dashboard with interactive insights can be downloaded here

**Note**: Due to problems with my Microsoft account, the interactive Power BI content is not available in this portfolio. I will update it once the issue is fixed.


## Data Structure & initial Checks
Maven Market's database has seven tables: customes, products, stores, regions, calendar, returns, and orders, with a total of 289,511 rows across all tables.

![full_name](https://github.com/user-attachments/assets/5918f224-027c-44de-8bc9-a2f46f588e7a)

Before beginning the analysis, comprehensive quality checks were performed to ensure data preparation and to familiarize with Maven Market's datasets. The SQL queries for data preparation can be found [here](https://mramadhankesapi.github.io/SQL-Queries-for-for-Rama-Kesa-Portfolio/)


## Executive Summary
### Overview of Finding
Maven Market has achieved strong financial results, with a $1.05M profit and a 59% profit margin, driven by rapid growth in 1998 from expanding into Mexico and Canada. Revenue has increased by 112% compared to last year, thanks to expansion and strong product performance.

The USA is still the top revenue source, but Mexico’s rapid growth shows it could compete with the USA soon. Hermano is the top-selling brand, making up 3.21% of total sales, indicating high customer demand. Notably, Plato stands out with the highest profit margin of 63.6%, despite lower revenue, showing great operational efficiency. The next sections will look at key factors behind this performance and explore opportunities for growth.

Below is an overview from the Power BI dashboard, with additional examples provided throughout the report.

![EXE SUMMARY](https://github.com/user-attachments/assets/bd0dd2bb-cf1f-4b63-a099-699ba282fc71)


### Product Performance:
- Best Choice balances strong profit margins and sales targets, with $42,738 in revenue and a 60.6% profit margin. It shows a steady upward sales trend, making it a strong performer with high sales and proportional profits.
- Plato and BBB Best have high profit margins (63.6% and 62.1%, respectively), but lower sales around $30K. However, while BBB Best shows a better sales trend, Plato missed its 10% target last month. Adjusting the price slightly for both products could help attract more buyers.

**Note**: This report includes a drillthrough page for detailed product performance analysis. By clicking on a product brand in any of the pages, the report will automatically navigate to the product performance page, updating with data specific to the selected product.

![Product Detail 1](https://github.com/user-attachments/assets/195598bb-fa1b-4dbf-85ef-b5d122713b33)

![Product Detail 2](https://github.com/user-attachments/assets/05208946-c48f-4ad2-addf-44cd1ff62199)


### Customer Behaviors:
- Maven Market has had a total of 8,842 customers over the past two years, with most of them (8,060) in 1998. This shows strong customer growth, especially in that year.
- Maven Market has a high 98.8% retention rate, meaning most customers keep coming back. This shows that customers are happy and loyal to the brand.
- Bronze membership brings in the most revenue, especially from lower and middle-income customers. These customers find the benefits of the bronze membership, which are likely more affordable, better than having no membership at all (the "normal" status).

![Customer Behaviors](https://github.com/user-attachments/assets/430427b2-70be-4470-a048-4243dd164ed0)


### Operational Efficiency:
- USA stores achieve high revenue per SQFT ($3.24) with a low order frequency (28), indicating fewer but higher-value purchases. In contrast, Mexico has a higher order frequency (66) but lower revenue per SQFT ($1.74), suggesting frequent but smaller transactions. The - - opportunity lies in boosting order frequency in the USA and Canada while increasing order values in Mexico to balance both performance metrics.
- We focus on USA stores as they have been running for two years. Stores like Store 14, Store 2, and Store 22 consistently underperform, earning under $0.50 revenue per square foot, highlighting the need for further evaluation.

![Operational Efficiency](https://github.com/user-attachments/assets/467e5d00-ead8-4167-be73-1aa82c7cbe2f)



