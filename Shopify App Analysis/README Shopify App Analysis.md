# Shopify App Analysis

## Project Overview
Reviewed the landscape of apps on the Shopify platform, using data scraped from publicly available Shopify websites, and to figured out what key factors played into the success of a Shopify app.

![image](https://github.com/murry-kristy/Data_projects_TripleTen/blob/main/Shopify%20App%20Analysis/Shopidy%20Dashboard%201%20Landscape.png)

![image](https://github.com/murry-kristy/Data_projects_TripleTen/blob/main/Shopify%20App%20Analysis/Shopidy%20Dashboard%202%20Reviews.png)

![image](https://github.com/murry-kristy/Data_projects_TripleTen/blob/main/Shopify%20App%20Analysis/Shopidy%20Dashboard%203%20App%20Reviews.png)

## Files
- README.md
- Raw Data: <a href='https://practicum-content.s3.us-west-1.amazonaws.com/data-eng/BIA/Dataset/shopify.xlsx' target=_blank><u>here</u></a>
- Project Requirements: <a href='https://github.com/murry-kristy/Data_projects_TripleTen/blob/main/Shopify%20App%20Analysis/Shopify%20App%20Analysis%20Project%20Reqs.md' target=_blank><u>here</u></a>
- Project Summary: <a href='https://github.com/murry-kristy/Data_projects_TripleTen/blob/main/Shopify%20App%20Analysis/shopify%20App%20Analysis%20Summary.pdf' target=_blank><u>here</u></a>
- Reviewer Comments: <a href='https://github.com/murry-kristy/Data_projects_TripleTen/blob/main/Shopify%20App%20Analysis/Reviewer%20Comments%20Shopify%20App.png' target=_blank><u>here</u></a>

## Table of Contents
| Tab Title| Description | 
| -------- | ------------|
| Description | Basic information about the project goals and final deliverables. |
| Data | Overview of the data source |
| Assumptions | List of assumptions regarding the provided dataset made based on the task objectives and data. |
| Process | General outline of the steps taken during the analysis. |
| Findings | Insights gathered after the data analysis. |

## Description
- 3 Power BI Dashboards.
- Includes data analysis, KPI cards, and charts.

## Data
The Excel file provided by TripleTenwas was public data scraped from the Shopify App Store. <a href='https://practicum-content.s3.us-west-1.amazonaws.com/data-eng/BIA/Dataset/shopify.xlsx' target=_blank><u>here</u></a>
1. `'shopify.xlsx'`: Excel Workbook containing 4 sheets:
    - `'apps'`: Details of the apps on the Shopify apps marketplace
    - `'apps_categories'`: Join tables to connect apps with categories
    - `'categories'`: Categories of the apps. Each app has multiple categories
    - `'reviews'`: Each review (row) contains information on user opinion about the related app (rating and comment). Also, it contains the response from the developer if present.

## Assumptions
- The scraped data from Shopify websites is current and accurate.
- The data in the shopify.xlsx file is complete and consistent, with minimal missing values or inconsistencies.
- The provided column names and data types in the tables accurately reflect their content.
- The user reviews are authentic and reflect how useful users find each review.

## Process
1. Found key statistics on the types of apps in the Shopify market based on review count and average ratings using line charts and scatterplots. 
2. Analyzed reviews by creating columns with aggregated data to match ratings with helpful reviews with bar charts.
3. Compared the average ratings with the total developer answers using a scatterplot. 

## Findings
- New apps are more likely to be rated early in their deployment.
- When the number of reviews increase, the average rating tends to stabilize between 4-5 indicating consistent user satisfaction.
- Reviews are higher for an app if a developer answers the review.
- Reviews that have been voted as helpful have a weighted average of 5.48.
- The app developer "Elfsight" has the highest combined ratings at 135 stars.
- The app developer "Pictorem" has the highest average helpful reviews at 50.
- The app developer "Hextom" has responded to the highest amount of reviews at 31,443 responses.
