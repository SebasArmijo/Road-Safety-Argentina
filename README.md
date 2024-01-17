# Road Safety Argentina

**Welcome to the Road Safety Argentina project!** This initiative is a critical step towards enhancing road safety and minimizing traffic accidents in Argentina. Given the profound impact of road traffic accidents on public health, community safety, and infrastructure, this project is not just about data analysis; it's about saving lives and making our roads safer for everyone. Through detailed data analysis and strategic KPI implementation, we aim to provide actionable insights to local authorities to significantly reduce fatalities and improve road safety in Buenos Aires. Dive into this README to understand our project's scope, approach, and the powerful insights we've uncovered.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Data Preparation](#data-preparation)
3. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
4. [Key Performance Indicators (KPIs)](#key-performance-indicators-kpis)
5. [Power BI Dashboard](#power-bi-dashboard)
6. [Resources](#resources)


## Project Overview
The Road Safety Argentina project aims to address the critical issue of road traffic accidents in Argentina, with a focus on reducing mortality rates and improving road safety in Buenos Aires. The Mobility and Road Safety Observatory (OMSV), under the Transportation Secretariat of the Autonomous City of Buenos Aires, has commissioned this data analysis project to inform policy and intervention strategies.

## Data Preparation
The initial phase of the Road Safety Argentina project involved a comprehensive data preparation and transformation (ETL) process. This process was crucial in ensuring the data's accuracy and usability for in-depth analysis. The key steps included:

- **Data Conversion**: Converting the original data, provided in Excel format, into more versatile CSV files. This conversion facilitated easier manipulation and analysis of the data.
- **Data Segregation**: Creating two distinct datasets titled "Homicides" and "Victims" to enable focused analysis on different aspects of road safety.
- **Data Cleaning**: Rigorous cleaning was undertaken to ensure the data's integrity. This involved rectifying inconsistencies, handling missing values, and standardizing data formats.
- **Weather Data Integration**: A significant challenge was the integration of accurate weather data, which required identifying and utilizing a reliable API for Argentine weather conditions. This step was crucial to explore potential correlations between weather patterns and road accidents.

## Exploratory Data Analysis (EDA)
The EDA phase was instrumental in uncovering insights and guiding the project's direction. The following key activities were performed:

- **Statistical Analysis**: A thorough examination of basic statistical measures (mean, median, variance, etc.) provided a foundational understanding of the data's characteristics.
- **Distribution Analysis**: Investigating the distribution of accidents across different times, locations, and conditions helped identify patterns and hotspots, crucial for targeting interventions.
- **Correlation Study**: An in-depth analysis was conducted to explore correlations between various factors such as accident times, locations, vehicle types, and weather conditions. While correlations with weather were generally minimal, this analysis offered valuable insights into other contributing factors.
- **Graphical Representations**: Various visualization techniques were employed to better understand and communicate the data.
- **Insight Generation**: The EDA process led to several key insights, such as the identification of high-risk areas and times, and the impact of specific vehicle types on accident rates. These insights were pivotal in formulating targeted safety measures and interventions.

The findings from the EDA were crucial in shaping the subsequent stages of the project, particularly in the development of the Power BI dashboard and the selection of Key Performance Indicators (KPIs).

## Key Performance Indicators (KPIs)
Three KPIs were defined:
1. **Homicide Rate Reduction**: Aim to reduce traffic accident homicides by 10% in CABA.
2. **Fatal Motorcycle Accident Reduction**: Target a 7% reduction in fatal motorcycle accidents in CABA.
3. **Nighttime Traffic Accident Reduction**: Achieve a 5% reduction in nighttime traffic accidents in CABA.

## Power BI Dashboard
The Power BI Dashboard is a cornerstone of the Road Safety Argentina project, designed to present complex data in an accessible and visually compelling format. The dashboard serves multiple functions, from highlighting key trends to enabling detailed analysis. The following components are central to the dashboard:

- **Main Page Overview**: This page acts as the dashboard's hub, presenting a comprehensive overview of road safety data. It features:
  - **Trends Over Time**: Interactive charts displaying accident trends over various timeframes, allowing users to observe patterns and changes.
  - **Victim Age Distribution**: Graphs showing the age distribution of accident victims, providing insights into the demographics most affected by road accidents.
  - **Accident Heat Maps**: Visual heat maps pinpointing accident hotspots within the city, helping to identify areas requiring immediate attention.
  - **Fatality Counts**: A counter tracking the number of fatalities, offering a stark reminder of the human cost of road accidents.

- **KPI Exposition Pages**: Each KPI has its dedicated page, allowing for a deep dive into the specific metrics and their impact on road safety. These pages include:
  - **KPI Metrics Visualization**: Charts and graphs that track the progress of each KPI against its targets, offering a clear view of the project's impact.

## Resources
- [Datasets](https://github.com/SebasArmijo/Road-Safety-Argentina/tree/master/Data/Processed): Access the datasets used in the analysis.
- [Images](https://github.com/SebasArmijo/Road-Safety-Argentina/tree/master/Data/Images): View project-related dashboard visualizations.
- [Workbooks](https://github.com/SebasArmijo/Road-Safety-Argentina/tree/master/Workbooks): Access analytical workbooks and notebooks.

