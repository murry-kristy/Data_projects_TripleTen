# Zomato Analysis

## Project Overview

- BUSINESS DESCRIPTION:
Zomato is a multinational restaurant aggregator company.

- BUSINESS OBJECTIVE:
Identify and profile Zomato's customer segments based on demographics (gender, age, monthly income, occupation) and spending behaviors to enhance target marketing efficiency.

- BUSINESS QUESTIONS:
1. What is the demographic distribution (gender, age, monthly income, occupation) of Zomato’s customer base? 
2. How do spending behaviors differ among customers? 
3. What are the different customer segments based on recency, frequency, and monetary value?
4. What marketing strategies could Zomato implement in targeting specific customer segments to retain customers and increase sales? 

<image src='https://github.com/murry-kristy/Data_projects_TripleTen/blob/main/Zomato%20Analysis/Demographics%20Dashboard.png'>
<image src='https://github.com/murry-kristy/Data_projects_TripleTen/blob/main/Zomato%20Analysis/Customer%20Segment%20RFM%20Dashboard.png'>
<image src='https://github.com/murry-kristy/Data_projects_TripleTen/blob/main/Zomato%20Analysis/RFM%20Demographics%20Dashboard.png'>

Tableau Share Link: <a href='https://public.tableau.com/shared/F7BMZYPJF?:display_count=n&:origin=viz_share_link' target=_blank><u>here</u>.</a>

## Files
- README.md
- Raw Data:
  - Orders Table: <a href='https://github.com/murry-kristy/Data_projects_TripleTen/blob/main/Zomato%20Analysis/Zomato%20Orders%201.csv' target=_blank><u>here</u>.</a>
  - Users Table: <a href='https://github.com/murry-kristy/Data_projects_TripleTen/blob/main/Zomato%20Analysis/Zomato%20Users%202.csv' target=_blank><u>here</u>.</a>
  - Segment Table: <a href='https://github.com/murry-kristy/Data_projects_TripleTen/blob/main/Zomato%20Analysis/Segment%20Table.xlsx' target=_blank><u>here</u>.</a>
  - RFM Table: <a href='https://github.com/murry-kristy/Data_projects_TripleTen/blob/main/Zomato%20Analysis/RFM%20Table.xlsx' target=_blank><u>here</u>.</a>
- Project Requirements: <a href='https://github.com/murry-kristy/Data_projects_TripleTen/blob/main/Zomato%20Analysis/Zomato%20Analysis%20Project%20Reqs.md' target=_blank><u>here</u>.</a>
- Project Report:<a href='https:https://github.com/murry-kristy/Data_projects_TripleTen/blob/main/Zomato%20Analysis/Final%20Project%20Presentation%20by%20Kristy%20Murry.pdf' target=_blank><u>here</u>.</a>
- Reviewer Comments: <a href='https://github.com/murry-kristy/Data_projects_TripleTen/blob/main/Zomato%20Analysis/Zomato%20Reviewer%20Comments.png' target=_blank><u>here</u>.</a>
- Models: <a href='https://github.com/murry-kristy/Data_projects_TripleTen/blob/main/Zomato%20Analysis/Zomato%20Models.png' target=_blank><u>here</u>.</a>

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
This was a Customer Segmentation Analysis.
1. Explored the demographic and sales data in the User and Orders tables to create Tableau visualizations identifying customers' spending behaviors based on gender, age, monthly, income, and occupation.
2. Examined customer order data in the Orders table and created 2 Power BI visualizations identifying customer segments based on recency, frequency, monetary analysis, and demographics. 

## Data
TripleTen provided an archived file of 5 separate Excel files from the mock company Zomato. I used 2.
- `'Zomato data.zip'`: Compressed Excel files provided by team lead
    - `'orders'`: All orders made from the menu by all customers at all restaurants between Oct. 4th, 2017, and June 26th, 2020.
    - `'users'`: All customers who completed orders during the designated time frame and their demographic information.
    - `'Segment Table'`: Created table containing each group's index, segments, and score.
    - `'RFM Table'`: Created table including calculated fields for R, F, and M values and scores for each user id.

## Assumptions
1. The provided test datasets are accurate, complete, and consistent.
2. Missing values or inconsistencies are minimal and will not significantly impact the analysis.
3. The column descriptions accurately reflect the content of each table.
4. The provided tables (orders and users) contain all the necessary information for the chosen analysis.
5. Zomato's business context and industry trends are considered while interpreting the data.

## Findings
**Demographic Segmentation Analysis** 
- Majority of customers are MALES (57+K) compared to females (42+K) out of 100K. However, females have a higher average order value ($80) compared to males ($78).
- The age group of 20-29 has the greatest number of total customers (89+K) and has the highest total spend ($10+M).
- Customers with “no monthly income” make up the bulk at 48+K; with customers making between $25K and $50K coming in second at 17+K.
- Students comprise the largest occupation distribution of total orders at 1.2+M out of 2.4+M.
- August has the highest average order quantity (19) and the average sales amount ($90).
- Overall, the average order size is 16; average order frequency (AOF) is 1.5; average order value (AOV) is $78.78; and the customer lifetime value is $355.20/3 years. 

**RFM Segmentation Analysis**
- Top 2 customer segments are the “Potential Loyalists” with 22% and “New Customers” with 18% of total customers.
  - Zomato may have invested heavily in customer acquisition through marketing campaigns, partnerships with restaurants, and introductory discounts, leading to a significant influx of new users. 
  - "Potential loyalists" likely result from customers responding positively to these campaigns but haven’t yet fully transitioned into loyal or champion customers.
- Bottom 2 customer segments are the “Cannot Lose Them” with <1% and “At-Risk” with 7% of total customers. 
  -  Customers at the lower end of the value chain may churn early (before reaching the "Cannot Lose Them" stage) due to dissatisfaction, switching to competitors, or reduced interest in online food delivery. 
  - This would reduce the size of the "At-Risk" segment, as many customers leave the ecosystem entirely before reaching this stage. 
- Avg. recency of orders is 68 months (length may be due to older data), avg.
    frequency is 2 orders during that time, and avg. spend is $5.87. 

**RFM Demographics Segmentation Analysis**
- Gender: The largest segment “Potential Loyalist” is comprised of 9+K MALES and 7+K FEMALES compared to the smallest segment “Cannot Lose Them” which is comprised of 313 males and 242 females. 
- Age: The largest segment “Potential Loyalist” is comprised of 15+K customers with ages between 20-29, 1+K customers with ages between 30-39, and 219 customers with ages under 20. This is in comparison to the smallest segment “Cannot Lose Them” which is comprised of 506 customers with ages between 20-29, and 46 customers with ages between 30-39. 
- Monthly Income: The largest segment “Potential Loyalist” is comprised of approx. 2K customers with a monthly income from $10K to $25K, 3K customers with a monthly income from $25K to $50K, 1+K customers with a monthly income below $10K, 3K customers with a monthly income greater than $50K, and 8+K customers with no monthly income. This is in comparison to the smallest segment “Cannot Lose Them” which is comprised of approx. 66 customers with a monthly income from $10K to $25K, 102 customers with a monthly income from $25K to $50K, 40 customers with a monthly income below $10K, 91 customers with a monthly income greater than $50K, and 256 customers with no monthly income. 
- Occupation: The largest segment “Potential Loyalist” is comprised of 5+K employees, 398 housewives, 2+K self-employed, and 9+K students compared to the smallest segment “Cannot Lose Them” which is comprised of 168 employees, 88 self-employed, and 290 students. 

## Recommendations
**Demographic Segmentation Analysis**
1. Male customers are more likely to respond to promotions tailored to fast/easy meals, so target marketing efforts accordingly to grow this market share. Females have a higher average order value, so upsell higher-value menu items/restaurants to them.
2. The age group of 20-29 often prioritizes convenience and speed, leading to more frequent orders from quick-service restaurants. They also engage more with app-based promotions and loyalty reward programs. So, target marketing to this group with app-based promotions and loyalty reward programs from quick-service restaurants. 
3. Most students with “no monthly income” have restricted budgets, so prefer restaurants marketing “meal deals” and discounts. They also spend more during breaks (school, holidays, social events) when they’re free from school commitments (Ex.August). Therefore, target “meal deal” discounts and promotions to students during August to increase sales and order frequency. 

**RFM Segmentation Analysis**
1. A large "potential loyalist" group is a prime opportunity to nurture and convert these customers into loyalists and champions through targeted engagement, personalized communication, and loyalty programs.
2. “New” customers represent a vital pool for long-term growth if nurtured properly with strong onboarding, easy-to-use interfaces, and attractive offers. 
3. Be aware of threats, in other words, the small size of the "Cannot Lose Them" and "At-Risk" groups may create a false sense of security. If they churn, it could significantly impact revenue and brand perception. 
4. Implement personalized marketing campaigns for “Potential Loyalists” and “New” customers to accelerate their movement into higher-value segments like “Champions”. 
5. Continuously monitor and address the concerns of “At-Risk” customers to prevent churn, even if the segment appears small. 

**RFM Demographics Segmentation Analysis**
1. The largest "Potential Loyalist" segment is the male student (age 20-29) with no income, so there is a is a prime opportunity to nurture and convert them into “Loyalists” and “Champions” through targeted engagement using loyalty programs and app-based promotions tailored to fast/easy meal deals during August. 
2. The smallest "Cannot Lose Them" segment is also the male student (age 20-29) with no income, so be aware of their spending behaviors because if they churn, it could still impact revenue and brand perception.
3. Females have a higher average order value, so target them a greater assortment of premium restaurants/menu items to increase their brand engagement and loyalty with the ultimate goal of converting the 7+K “Potential Loyalists” females into “Loyalists” and “Champions”. 
