# Superstore Returns Analysis

## Project Overview
Prepare an analysis for the CEO of Superstore to help them understand what is causing customers to return their orders and how to reduce the volume of returned orders.

Dashboard: Understanding Returns by Product Categories Over Time

![image](https://github.com/murry-kristy/Data_projects_TripleTen/blob/main/Superstore%20Returns%20Analysis/Superstore%20Returns%20by%20Product%20Categories%20Over%20Time%20Dashboard%20Screenshot.png)

Dashboard: Understanding Return Rate by Category & Region/State

![image](https://github.com/murry-kristy/Data_projects_TripleTen/blob/main/Superstore%20Returns%20Analysis/Superstore%20Returns%20by%20Category%20and%20Region%20State%20Dashboard%20Screenshot.png)

Root Causes of Returns

![image](https://github.com/murry-kristy/Data_projects_TripleTen/blob/main/Superstore%20Returns%20Analysis/Superstore%20Returns%20Summary%20Screenshot.png)

Recommendations

![image](https://github.com/murry-kristy/Data_projects_TripleTen/blob/main/Superstore%20Returns%20Analysis/Superstore%20Returns%20Recc%20Screenshot.png)

Tableau Public Share Link: <a href='https://public.tableau.com/views/KristyMurrySprint5Project1/SuperstoreReturnsPresentation?:language=en-US&:sid=06DA54D870624B109B37BD9A96C60DD1-0:0&:redirect=auth&:display_count=n&:origin=viz_share_link' target=_blank><u>here</u>.</a> 

## Files
- README.md
- Raw Data: <a href='https://github.com/murry-kristy/Data_projects_TripleTen/blob/main/Superstore%20Returns%20Analysis/Superstore%20Project%205%20Data.xls' target=_blank><u>here</u>.</a>
- Project Presentation: <a href='https://github.com/murry-kristy/Data_projects_TripleTen/blob/main/Superstore%20Returns%20Analysis/Superstore%20Returns%20Presentation.pdf' target=_blank><u>here</u>.</a>
- Project Requirements: <a href='https://github.com/murry-kristy/Data_projects_TripleTen/blob/main/Superstore%20Returns%20Analysis/README%20Superstore%20Returns%20Project%20Requirements.md' target=_blank><u>here</u>.</a>
- Project Rubric: <a href='https://github.com/murry-kristy/Data_projects_TripleTen/blob/main/Superstore%20Returns%20Analysis/Sprint%205%20Project%20Rubric.pdf' target=_blank><u>here</u>.</a>
- Reviewer Comments: <a href='https://github.com/murry-kristy/Data_projects_TripleTen/blob/main/Superstore%20Returns%20Analysis/Reviewer%20Comments%20Superstore%20Returns%20.png' target=_blank><u>here</u>.</a>

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
- 7 Tableau Visualizations, 2 Dashboards, and a 13-page Story Presentation.
- Includes data analysis, charts, dashboard, and Tableau story.

## Data
1. Excel spreadsheet: Add link
- - `'Superstore.xls'`: each row corresponds to one product sold; sheets were LEFT JOIN'd
    - `'orders'`: details all fields for each ordered item
    - `'returns'`: details all fields for each returned item

## Assumptions
- Profits from sales are totaling in the negative.	
- There is one or more causes for negative profits directly related to orders and returns.
- The operations department will need to make changes.

## Process
1. LEFT JOIN'ed `Returns` table to `Orders` table.
2. Made `Returned` field into calculated field where null values are 0 and `Yes` values are 1.
3. Built a scatterplot showing total sales vs. total returns aggregated by product subcategory.
4. Created a bar chart showing return rates by product category.
5. Analyzed customer return rates by using a filter to remove customers with only 1 order.
6. Visualized return rates by state and region with a map.
7. Analyzed return rates by a time measure (month).
8. Generated two-composite charts showing return rates for by product category and time; and by product category and region.
9. Created a low-fidelity mock-up for my dashboard after sketching 3 variations.
10. Built a dashboard for monitoring returns in Tableau using empty containers. 
11. Constructed a story arc for the presentation by drafting a story using only captions for each story point.
12. Added content to the story points using all worksheets.
13. Delivered presentation in PDF format. 

## Findings
- The 'technology' product category, as well as the 'binders and phones' sub-category have the highest return rates, and the highest number of total returns.  
- The highest return rates occur during August and September.
- The western United States (specifically Utah and California) have the highest return rates.
- Customers (Hilary Holden and Roland Murray) have the highest return rates with both at 100%. 
- Possible root causes include:
  - Product quality, compatibility, and complexity.
  - Rapid product evolution and obsolescence.
  - Product setup and installation difficulties.
  - Back-to-school shopping.
  - E-commerce giants and tech companies are headquartered in the western region.
  - Lenient return policies.
  - Extended shipping times, handling errors, or damage during transit to western region.
  - Low customer satisfaction.
  - High customer expectations and performance variability.

## Recommendations
1. Create a SURVEY with questions related to each root cause of high returns and send to the top return rate customers. 
2. Analyzing return reasons, customer feedback, and return data trends can help identify the main drivers for high returns, allowing the Superstore to adjust marketing, product details, or quality control to reduce them. 
