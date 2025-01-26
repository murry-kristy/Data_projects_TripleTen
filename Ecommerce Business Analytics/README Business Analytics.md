# E-commerce Business Analysis

## Project Overview
An e-commerce cohort analysis, transforming raw transaction logs into meaningful and actionable business insights. Conversion funnel was created to analyze how users interacted with the website (e.g., how effectively the website transformed product page views into purchases). Acquisition cohorts were built to track monthly metrics (retension rates) based on first purchase dates. 

Image links

- Complete Project (Google Sheet Doc): <a href='https://docs.google.com/spreadsheets/d/180Q3sWSKGBXhjlHS2azM_mDaYg1iJjP-ujVu_l5TpD4/edit?gid=38637670#gid=38637670' target=_blank><u>here</u>.</a>

## Files
- README.md
- Raw Data Google Spreadsheet: <a href='https://docs.google.com/spreadsheets/d/1qWRY5svKGkJRyYNv7K4XvEGm9FpcoJhH5G0p4Qbq0V0/edit?usp=sharing' target=_blank><u>here</u>.</a>
- Complete Project (Google Sheet Doc): <a href='https://docs.google.com/spreadsheets/d/180Q3sWSKGBXhjlHS2azM_mDaYg1iJjP-ujVu_l5TpD4/edit?gid=38637670#gid=38637670' target=_blank><u>here</u>.</a>
- Project Requirements:
- Reviewer Comments: 

## Table of Contents
| Tab Title| Description | 
| -------- | ------------|
| Description | Basic information about the project goals and final deliverables. |
| Data | Overview of the data source |
| Assumptions | List of assumptions regarding the provided dataset made based on the task objectives and data. |
| Process | General outline of the steps taken during the analysis. |
| Findings | Insights gathered after the data analysis. |

## Description
- 8 page spreadsheet (Google Sheets)
- Includes: organizational tabs, raw data, processed data (conversion funnel, retention rates, purchase activity), data analysis (cohort analysis), and pivot tables.

## Data
The data contains information about user activity (or event) on the e-commerce website. Raw data spreadsheet: <a href='https://docs.google.com/spreadsheets/d/1qWRY5svKGkJRyYNv7K4XvEGm9FpcoJhH5G0p4Qbq0V0/edit?usp=sharing' target=_blank><u>here</u>.</a>
The dataset includes raw transaction logs where each row represents an activity, or event, by a user on the company’s website:
* `user_id`: unique customer IDs   
* `event_type`: the type of activity by the user   
* `category_code`: category of the product being viewed or purchased   
* `brand`: company that makes the product   
* `price`: price of the product, in USD   
* `event_date`: date of the user activity, in YYYY-MM-DD format   
* `'Table of Contents'`: empty table of contents sheet preformatted
* `'Executive Summary`: empty executive summary sheet preformated

## Assumptions
- The "raw_user_activity" sheet accurately provides a comprehensive record of all website activity within the specified timeframe (September 2020 - February 2021).
- Missing values or inconsistencies were minimal, therefore, not considered. 
- The data format, including columns and data types, is accurate and consistent.
- Only data pertaining to the user ID, event type, and transaction date was utilized.
- The conversion funnel displays the number of unique users at each stage, highlighting a decreasing percentage as users progress through the funnel.
- Retention rates are calculated based on monthly user cohort percentages and variations in user activity.

## Process
1. Explored, cleaned, and filtered the data.
2. Built a conversion funnel comprised of 3 stages to better understand user interaction with the website using unique user count.
3. Calculated total conversion rates and conversion rates to the next step.
4. Created acquisition cohorts based on the month of users' first purchase by tracking, organizing, and analyzing monthly metrics data.
5. Calculated overall rentention rates using those cohorts.
6. Used advanced spreadsheet best practices to format, organize, and document the final report.  

## Findings and Reccomendations
- Conversion Funnel: 
  - Total Conversion Rate Insights: 29% of users that viewed the web page added a product(s) to their shopping cart, and only 10% actually purchased something. 
  - Conversion Rates to Next Step Insights: 29% of users that viewed the web page added a product(s) to their shopping cart (same as total conversion rate), and 36% of those users
    actually purchased a product (an increase of 26% compared to the total conversion rate).
  - Recommendations: Average e-commerce conversion rates are usually around 2.5-3%, and our rates are higher, so that's positive. However, many strategies can help improve conversion
    rates such as:optimizing site speeds because customers are likely to leave pages that don't load quickly; simplifying the checkout process so it's easy for customers to
    understand; and abandoned cart recovery where emails can remind users that they left products behind. 
- Retention Rates: 
  - Insights: Customers who made their first purchase in September 2020 had the highest retention rates over months 1 (13%), 2 (6%), and 4 (3%). Therefore, business activities
    (e.g., marketing campaigns) occurring during the September 2020 timeframe need to be investigated to determine which ones possibly led to these successful metrics so they can be
    duplicated or improved.
  - Recommendations: Several strategies can improve e-commerce retention rates such as:
    1) Instituting loyalty programs that encourage customers to keep buying after their first purchase.
    2) Improving the post-purchase experience to positively reinforce customer satisfaction.
    3) Offering personalized customer service. 
    4) Conducting surveys of customers making their first purchase to learn how to improve business processes so they buy again, and again.