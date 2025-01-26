# Zuber Rideshare Analysis

## Project Overview
Project analyzes available competitor information to investigate patterns for a rideshare company (Zuber) who's launching in Chicago. The goal is understand passenger preferences and the impact of weather on ride frequency, using SQL. 
<img src="https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/Images/Zuber%20Database.png" alt="First SQL Task Page">

- Complete Project Analysis: <a href= 'https://github.com/murry-kristy/Data_projects_TripleTen/blob/main/Zuber%20Rideshare%20Analysis/Zuber%20Rideshare%20Analysis.pdf'><u>Project Analysis.txt</u></a>

## Files
- README.md
- <a href= 'https://github.com/murry-kristy/Data_projects_TripleTen/blob/main/Zuber%20Rideshare%20Analysis/Zuber%20Project%20Requirements.md'><u>Project Requirements.txt</u></a>
- <a href= 'https://github.com/murry-kristy/Data_projects_TripleTen/blob/main/Zuber%20Rideshare%20Analysis/Zuber%20Table%20Scheme.png'><u>Table Scheme.txt</u></a>
- <a href= 'https://github.com/murry-kristy/Data_projects_TripleTen/blob/main/Zuber%20Rideshare%20Analysis/Zuber%20Rideshare%20Analysis.pdf'><u>Project Analysis.txt</u></a>

## Table of Contents
| Section Title | Description |
| ----------- |----------- |
| Description | Describes the final product's purpose, software, format, and included visuals. |
| Data | Describes the source of data, included files, tables, and fields. |
| Table Scheme | Relationship between the tables in the Zuber dataset. |
| Process | A general outline of how this project formed from start to finish. |
| Assumptions | Describes assumptions to include given by TripleTen and assumptions made based on the data and task. |
| Findings | Insights learned from the data analysis. |

## Description:
- 6 Step SQL query.
- Exploratory data analysis and investigation of whether the duration of rides from the Loop to O'Hare International Airport changes on rainy Saturdays.

## Data
A database with info on taxi rides in Chicago provided by TripleTen:
- `'neighborhoods'` table: data on city neighborhoods
    - `'name'`: name of the neighborhood
    - `'neighborhood_id'`: neighborhood code
- `'cabs'` table: data on taxis
    - `'cab_id'`: vehicle code
    - `'vehicle_id'`: the vehicle's technical ID
    - `'company_name'`: the company that owns the vehicle
- `'trips'` table: data on rides
    - `'trip_id'`: ride code
    - `'cab_id'`: code of the vehicle operating the ride
    - `'start_ts'`: date and time of the beginning of the ride (time rounded to the hour)
    - `'end_ts'`: date and time of the end of the ride (time rounded to the hour)
    - `'duration_seconds'`: ride duration in seconds
    - `'distance_miles'`: ride distance in miles
    - `'pickup_location_id'`: pickup neighborhood code
    - `'dropoff_location_id'`: dropoff neighborhood code
- `'weather_records'` table: data on weather
    - `'record_id'`: weather record code
    - `'ts'`: record date and time (time rounded to the hour)
    - `'temperature'`: temperature when the record was taken
    - `'description'`: a brief description of weather conditions, e.g. "light rain" or "scattered clouds"

## Table Scheme:

![image](https://github.com/murry-kristy/Data_projects_TripleTen/blob/main/Zuber%20Rideshare%20Analysis/Zuber%20Table%20Scheme.png)

## Process:
1. Analyzed taxi rides by the company for specific dates, sorting by trip count.
2. Analyzed rides for companies containing specific keywords, grouping by company name.
3. Retrieved neighborhood IDs for O'Hare and Loop.
4. Categorized weather conditions by hour.
5. Retrieved Saturday rides from Loop to O'Hare, including weather and duration.
6. Sorted the results.

## Assumptions:
- There is no direct connection between the `trip` and `weather records` tables in the database.
- The `neighborhood_id` is the Primary Key for the `neighborhood` table.
- The `cab_id` is the Primary Key for the `cabs` table. 
- The `trip_id` is the Primary Key for the `trips` table.
- The `record_id` is the Primary Key for the `weather_records` table.

## Findings:
1. The taxi company "Yellow Cab" had the highest number of taxi rides for Nov. 15-16, 2017 at 33,668 trips.
2. When searching SQL for a taxi company that contains the keyword "Yellow" or "Blue", the taxi company "Yellow Cab" had the highest number of taxi rides for Nov. 1-7, 2017 at 33,668 trips.
3. Compared the two most popular taxi companies "Flash Cab" and "Taxi Affiliation Services" with all other available companies for Nov. 1-7, 2017. It was found that "Flash Cab" had a total of 64,084 taxi rides;
   "Taxi Affiliation Services" had 37,583; and the "Other" category showed 335,771 which was significantly higher than each top company separate or combined.
4. The identifiers for the O'Hare neighborhood was 63 and Loop neighborhood was 50.
5. Retrieved weather conditions records breaking down all hours into 2 groups. "Bad" if the description included the words "rain" or "storm"; and "Good" for all others. 
6. A SQL table was printed to show all rides that started in the Loop neighborhood on a Saturday and ended at O'Hare. Tables included Start time, weather conditions, and duration.
