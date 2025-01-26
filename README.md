# T20-Cricket-data-analysis
![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)

# Overview

The Cricket Data Analytics project is a comprehensive data analysis initiative centered on the T20 Cricket World Cup 2022. This project uses Power BI to create an interactive dashboard that provides actionable insights into player and team performances. It also includes a feature to help users select the Best Playing XI for a team based on a well-defined set of performance criteria, such as batting averages, strike rates, bowling performances, and player roles (e.g., power hitters, anchors, finishers, and specialist bowlers).

# The project emphasizes:

Simplified data visualization for quick analysis of matches and player performances.
Robust data processing pipelines for accurate insights.
Enabling cricket enthusiasts, analysts, and coaches to make informed decisions using real-world data.
Key Features
Interactive Power BI Dashboard

Review and compare the performance of all players in the T20 Men's Cricket World Cup 2022.
Visualize key performance metrics for batsmen, bowlers, and all-rounders.
Identify standout players and trends across matches.
Best Playing XI Selection

Automatically select the best playing XI based on a pre-defined selection criterion.
Incorporates parameters such as batting averages, strike rates, bowling economy, and fielding metrics.
Advanced Insights

Highlight top-performing players in different categories, such as power hitters, anchors, finishers, and specialist bowlers.
Analyze trends and patterns that can guide decision-making for future matches or tournaments.
Performance-Based Team Confidence

The selected team has a 95% chance of winning based on performance data and analytical modeling.
How to Interact with the Dashboard
To explore the interactive Power BI dashboard:

# Project Workflow
The project followed a structured, step-by-step approach:

1. Requirement Scoping
Collaborated with a Subject Matter Expert (SME) to define the project's objectives and problem statements.
Key objectives included creating a performance analysis dashboard and facilitating the selection of the Best XI players.
2. Data Collection
Sources:
Match data and player statistics were scraped from ESPNcricinfo.
Player career performance data was gathered using BrightData.
Process:
Used the Python library BeautifulSoup to scrape data.
Extracted JSON files, converted them into dataframes in Jupyter Notebook, and exported them as CSV files for further analysis.
3. Data Cleaning and Preprocessing
Performed initial data cleaning using Python and Pandas:
Corrected player names to ensure consistency.
Handled missing values in datasets.
Linked match IDs and established relationships between various data points.
4. Data Transformation
Conducted data transformation using Power Query in Power BI:
Merged datasets for a cohesive data structure.
Performed data transformations for optimal dashboard visualization.
5. Data Modeling
Built relationships between datasets using primary keys such as team IDs and match IDs.
Developed calculated columns, measures, and parameters using DAX (Data Analysis Expressions) to enable advanced analysis and visualization.
6. Dashboard Development
Designed and implemented an interactive, user-friendly dashboard in Power BI:
Utilized advanced visualizations to display match and player performance metrics.
Included features to dynamically select and evaluate the Best XI players.
7. Insights Collection
Extracted key insights into player performances and tournament statistics:
Identified top performers in batting, bowling, and fielding.
Analyzed trends such as match-winning contributions and consistency.

# Detailed Explanation of Components
1. Data Collection
Match data, player statistics, and career details were scraped using ESPNcricinfo.
The JSON files were processed and converted into CSV files using Jupyter Notebook.
Career performance data of players was collected through BrightData for a comprehensive analysis.
2. Data Transformation
Initial data cleaning was performed using Pandas to ensure consistency and accuracy.
Transformed the cleaned data into a dashboard-ready format using Power Query.
3. Data Modeling
Created robust data models by linking datasets using primary keys (e.g., team and match IDs).
Built calculated columns and measures in DAX to analyze key performance metrics dynamically.
4. Dashboarding
Designed a visually appealing and user-friendly dashboard in Power BI.
Features include performance metrics, Best XI selection, and tournament insights.

# Insights and Outcomes
1. The Power BI dashboard provides a comprehensive view of the T20 Cricket World Cup 2022, enabling detailed performance analysis of all players and teams.
2. The "Best XI" feature helps users create a winning team based on defined performance metrics.
3. The project demonstrates the integration of web scraping, data preprocessing, transformation, and advanced visualization techniques.

# Screenshots of the Dashboard

![ss1](https://github.com/user-attachments/assets/359e6a59-7ea5-40f0-a165-30611d81e0dd)
![ss2](https://github.com/user-attachments/assets/382a9906-925d-4b47-bf83-c5f3943c97e2)
![ss4](https://github.com/user-attachments/assets/c3835633-9937-4b9f-8068-86dc4157f75b)
![ss5](https://github.com/user-attachments/assets/78a6d15b-9b54-4b78-8cbf-6711ecf23b10)
![ss3](https://github.com/user-attachments/assets/d21ca37b-5d1a-4826-8bf1-e07c0320ba67)
