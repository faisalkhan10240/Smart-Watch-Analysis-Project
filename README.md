Smart Watch Health Data Analysis ⌚📊
This project explores fitness tracker data to uncover deep insights into human activity, calorie expenditure, and daily health habits. By combining Python for data science and SQL for structured querying, this analysis transforms raw data into actionable wellness patterns.
🚀 Project Overview
The analysis focuses on processing daily activity logs to understand the relationship between sedentary behavior and physical activity. The project includes data cleaning, feature engineering, user segmentation, and statistical visualization to provide a 360-degree view of user health trends.
🛠️ Tech Stack
 * Language: Python
 * Data Analysis: Pandas, NumPy
 * Data Visualization: Matplotlib, Seaborn, Plotly
 * Database Management: SQLite3
🔍 Key Features & Analysis
1. Feature Engineering (Python)
 * Total Active Minutes: Combined Very Active, Fairly Active, and Lightly Active minutes.
 * Sedentary Percentage: Calculated the ratio of inactive time to total time to identify health risks.
 * Intensity Index: Developed a metric to measure the quality of movement (Very Active Minutes / Total Active Minutes).
 * Calories Per Step: Measured metabolic efficiency by dividing calories burned by total steps.
2. Structured Querying (SQL)
Using sqlite3, I performed complex data manipulations directly on the database:
 * User Performance: Ranked users by average daily steps using GROUP BY and ORDER BY.
 * Activity Benchmarking: Compared "Very Active" minutes against total calorie burn to validate activity intensity.
 * Sedentary Categorization: Used SQL CASE statements to classify days into "Extreme," "High," or "Moderate/Low" sedentary levels.
 * Efficiency Metrics: Queried calories-per-step to find the most active and efficient users.
3. User Segmentation
Users were classified into four distinct categories based on their behavior:
 * Sedentary Dominant: Users with a sedentary percentage > 75\%.
 * High Intensity: Users with an Intensity Index > 0.4.
 * Active Walkers: Users averaging > 10,000 steps daily.
 * Light Activity: All other users.
4. Visual Insights
 * Correlation Matrix: Analyzed the 0.59 correlation between steps and calories.
 * Time Analysis: Compared Weekday vs. Weekend activity, finding that sedentary time is slightly lower on weekends (977 min) compared to weekdays (996 min).
 * Distribution Plots: Visualized calorie distribution across user types using Seaborn boxplots.
📊 Sample Visualizations
 * Relationship between Calories & Total Steps: A scatter plot with an OLS trendline showing the positive impact of movement.
 * Daily Activity Breakdown: Pie charts representing the distribution of active vs. inactive minutes.
Would you like me to add a "How to Run" section or a more detailed breakdown of the SQL schema used in the project?
