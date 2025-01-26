# Superstore Operations Analysis

## Project Overview
Project goal was to advise the company by evaluating the store's operations and implementing strategies to enhance profitability and prevent bankruptcy using Tableau visualizations.

__Sub-Category Profit Centers & Loss Makers Per Region Dashboard__

![image](https://github.com/murry-kristy/Data_projects_TripleTen/blob/main/Superstore%20Operations%20Analysis/Sub-Category%20Profit%20Loss%20Per%20Region%20Dashboard.png)

__Return Rate Dashboard__

![image](https://github.com/murry-kristy/Data_projects_TripleTen/blob/main/Superstore%20Operations%20Analysis/Return%20Rates%20Dashboard.png)

__Advertising Spend Focus on States Worksheet__

![image](https://github.com/murry-kristy/Data_projects_TripleTen/blob/main/Superstore%20Operations%20Analysis/Advertising%20Spend.png)

- Complete Project Analysis (Tableau Public link): <a href='https://public.tableau.com/views/KristyMurrySprint4TableauProject/Sub-CategoryProfitCentersLoss-MakersPerRegion?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link' target=_blank><u>Tableau Public project link </u></a>

## Files
- README.md
- Raw Data: <a href='https://github.com/murry-kristy/Data_projects_TripleTen/blob/main/Superstore%20Operations%20Analysis/Superstore%20Raw%20Data%20Link.xls' target=_blank><u>Here</u></a>
- Project Requirements: <a href='
- Reviewer Comments: 
- Project Rubric:

## Table of Contents
| Tab Title| Description | 
| -------- | ------------|
| Description | Basic information about the project goals and final deliverables. |
| Data | Overview of the data source |
| Assumptions | List of assumptions regarding the provided dataset made based on the task objectives and data. |
| Process | General outline of the steps taken during the analysis. |
| Findings | Insights gathered after the data analysis. |
| Recommendations | Recommendations based on the data analysis. |


## Description
- 7 page visualization project using Tableau.
- Includes: data analysis, charts, and dashboards.

## Data
1. Excel spreadsheet:
   - `'Superstore.xls'`: each row corresponds to one product sold; sheets were LEFT JOIN'd
     - `'orders'`: details all fields for each ordered item
     - `'returns'`: details all fields for each returned item

2. Tableau sheets:
   - Sub-Category Profit Centers & Loss Makers Per Region Dashboard
     - Analysis of total profits and losses by product sub-category and region, including product profitability totals.
   - Return Rate Dashboard
     - Overview of return rate percentages among products and customers; and an evaluation of products based on average profits and average return rates.
   - Sub-Category Profit Centers & Loss Makers Per Region Worksheet
     - Analysis of total profits and losses by product sub-category and region.
   - Product Profitablility Worksheet
     - Evaluation of total profits among product sub-categories.
   - Advertising Spend Focus on States Worksheet
     - Investigation of the most profitable month/state combinations for advertising spend.
   - Return Rates Worksheet
     - Examination of return rate percentages among products and customers.
   - Product Average Profit vs. Average Return Rate Worksheet
     - Assessment of products based on average profits and average return rates.


## Assumptions
- Sales profits have dropped into negative values, resulting in losses.	
- Negative profits are attributed to one or more factors directly linked to orders and returns.
- Some products are not contributing to revenue generation.
- Sales vary depending on the time of year.
- The operations department will need to implement adjustments.
- The advertising department requires recommendations and guidance on developing a new strategy to boost sales.

## Process
1. Merged the orders and returns data using a left join on the primary key: order ID.
2. Identified profit and loss centers across various dimensions, including product sub-category and region.
3. Determined the top three state and month combinations where the company should intensify advertising efforts and calculated the optimal monthly advertising budget.
4. Analyzed product sub-categories with the highest customer returns and provided recommendations on which products the company should discontinue based on the data.

## Findings

__Profit & Losses__
- The two biggest profit centers were copiers in the West region (Total $35,293) and chairs in the East region ($22,827). 
- The two loss centers were binders in the Central region ($20,585) and Tables in the East region ($12,073).
  
__Advertising__   

- Advertising efforts should target the following month and state combinations, as they yielded the highest profit values.
   - Indiana - October  (Ave. Profit = $129)
   - Vermont - November (Ave. Profit = $119)
   - Vermont - April    (Ave. Profit = $67)
 
 __Product Returns & Profit__
- Copiers were the most successful product, generating the highest total profits ($76,304) and experienced the fewest total returns. 
- Tables were the least profitable product showing negative toal profits ($23,067) and experienced the highest number of total returns. 
- 8 products had return rates of 100%.
- Top 10 customers with the highest return rates showed return rates ranging from 86%-100%.
- Analyzing average profits against return rates revealed a few individual products that are not viable for sale, along with many others requiring further evaluation for continuation.

## Recommendations
1. Focus on the highest-performing products/regions (Copiers/West, Chairs/East) by investing more resources (e.g., inventory, marketing) into these products and regions to maintain
   or boost sales. Replicating success in other regions should also be considered. If a product performs well in one region, consider expanding it into similar regions with comparable demographics and demand. 
2. Focus marketing and advertising campaigns on Indiana in October, and Vermont in April and November, as these periods yielded the highest profit values.
3. Address the biggest loss-makers (Binders/Central, Tables/East). Recommend analyzing why certain products or regions are not generating profit (e.g., pricing issues, poor
   marketing, competition). If a product consistently underperforms across regions, it may be better to discontinue it and reallocate resources. Adjusting marketing, pricing, and distribution methods could also improve performance strategy.
   















 
