# Vacation Rental Market Analysis

## Project Overview
Project analyzes the short-term vacation rental market in Manhattan using Airbnb data by answering the following questions:
  
1. What neighborhoods are the most attractive for short-term vacation rentals?
2. What property sizes (i.e., number of bedrooms) are most popular for short-term vacation rentals?
3. Do different neighborhoods have different preferences for property sizes?

The best investment opportunities were identified using advanced shreadsheet techniques analyzing property types, occupancy rates, pricing trends, and delivering actionable insights to inform and shape their investment strategy.

- Complete Project Analysis: <a href='https://docs.google.com/spreadsheets/d/1--PPzOhVLWLxQigG588t-GNHkS3y0m9VrWpYY8RQFvY/edit?usp=sharing'><u>here</u></a>

## Files
- README.md
- <a href='https://docs.google.com/spreadsheets/d/1--PPzOhVLWLxQigG588t-GNHkS3y0m9VrWpYY8RQFvY/edit?usp=sharing'><u>Vacation Rental Market Analysis</u></a>
- 

## Table of Contents
| Tab Title| Description | 
| -------- | ------------|
| Data | Overview of the data source |
| Description | Basic information about the project goals and final deliverables. |
| Assumptions | List of assumptions regarding the provided dataset made based on the task objectives and data. |
| Process | General outline of the steps taken during the analysis. |
| Findings | Insights gathered after the data analysis. |

## Description
- 11 page spreadsheet (Google Sheets)
- Includes: organizational tabs, raw data (hidden), processed data, data analysis, pivot tables, and bar charts.

## Data
The data was one Google spreadsheet file provided by TripleTen, Copy can be found [HERE](https://docs.google.com/spreadsheets/d/1Z7KNEYs_YtQP57mWXRddPGAI3Sk-tPzLnCsdysCSw_c/edit?usp=sharing):
- `'nyc_airbnb_data.csv'`: each row corresponds to one listing on Airbnb in September 2022
    - `'data_dictionary'`: summary of field titles seen in the file and its data type
    - `'listings'`: uniquely listings available with all available data
    - `'calendar'`: listings with upcoming availabilities and date-type data

## Process
1. **Data Preparation**: Explored, organized, and cleaned the data using *Filtering* techniques. Key functions such as PROPER, TRIM, IF, ISNUMBER, FIND, ROUND, SUMIF, VLOOKUP, CHOOSE, and WEEKDAY were used.
2. **Neighborhood Analysis**: Identified the top-10 performing neighborhoods that should be considered for potential investment based on review frequency (*Pivot Table*).
3. **Property Size Analysis**: Determined the optimal property sizes for each neighborhood (*Pivot Table*).
4. **Occupancy Analysis**: Calculated the average occupancy rates for each listing (*Pivot Table*) and the average occupancy rates for each day of the week (*Pivot Table*).
5. **Revenue Analysis**: Calculated the estimated annual revenue for the most attractive listing (*Pivot Table*).
6. **Data Visualization**: Created visualizations to illustrate the occupancy rates by day of the week (*Bar Chart*) and top-10 performing neighborhoods (*Bar Chart*).
7. **Formatting and Organization**: Organized and formatted the spreadsheet with consistent font styles, colors, borders, and hidden columns for clarity throughout the report.
8. **Documentation**: Created organizational sheets like an executive summary, table of contents, assumptions log, and change log. 

## Assumptions
- Airbnb data provided as of August 19, 2024 is accurate and reliably reflects the current Manhattan short-term vacation rental market.
- Listings with a minimum night requirement of more than 7 days are not relevant for vacation rental properties, therefore, are not included.
- Listings with no reviews in the last 12 months are reasoned to be inactive.
- Only listings with high review ratings were considered.
- Super luxury or extremely low-priced listings were filtered out. 
- Calculated the annual revenue for the top neighborhood with 1 bedroom.

## Findings and Reccomendations
1. The top recommended neighborhoods for vacation rentals are as follows: Lower East Side, Hell's Kitchen, Harlem, Midtown, Upper West Side, Chelsea, East Village, East Harlem, West Village, and Nolita. Thereore,
   investments into properties located in these Manhattan neighborhoods are recommended.	
2. The top rental size is 1 bedroom. Lower East Side properties should have 1-bedrooms to meet demand. 	
3. Fridays have the highest occupancy rate out of the week, average occupancy is 89%. Advertising Friday availability or special weekend rates (starting on Fridays) would increase sales.
4. The estimated annual revenue of $105,584 for a Lower East Side 1-bedroom rental is based on an average price of $299.25/night and an average occupancy rate of 96%. Therefore, investments into properties within
   these metrics is recommended as a sound short-term rental investment in Manhattan.

