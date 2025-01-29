Project Requirements:

Create 3 Power BI pages with the following visuals:

1. App Landscape
- Create a KPI card that counts the unique number of apps.
- Build a Line Chart showing the sum of review counts over time (Y-axis) compared to the lastmod date (X-axis).
- Make a Scatterplot with reviews_count on the X-axis and average rating on the Y-axis, annotating interpretation with a text box.

2. Reviews
- Add a new column in the `Reviews` table for helpful_reviews using a DAX expression.   
- Make a Card displaying the average value of the new helpful_reviews column.   
- Create a new column in the `Reviews` table for developer_answered using a DAX expression.   
- Build a Scatterplot comparing average rating (Y-axis) by the developer_answered status (X-axis).   

3. App Reviews
- Create a new "many-to-one" relationship between the `Reviews` table (many) and the `Apps` table (one) using app_id.
- Add a Bar Chart with developer on the X-axis and the sum of ratings on the Y-axis. 
- Make a second Bar Chart showing developers (X-axis) against the average of helpful_reviews (Y-axis).
- Build a Bar Chart displaying developers by their responsiveness, filtering for apps with more than 500 reviews. 

4. Submission
- Share 8 screenshots for each project sub-question and submit.