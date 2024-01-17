# Road Safety Argentina

Welcome to the Road Safety Argentina project, dedicated to improving road safety and reducing traffic accidents in Argentina. This README provides an overview of the project, its objectives, and key components.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Data Preparation](#data-preparation)
3. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
4. [Key Performance Indicators (KPIs)](#key-performance-indicators-kpis)
5. [Power BI Dashboard](#power-bi-dashboard)
6. [Resources](#resources)

## Project Overview
The Road Safety Argentina project aims to address the critical issue of road traffic accidents in Argentina. These accidents, also known as traffic accidents or road incidents, involve vehicles on public roads and can have various causes, including collisions between cars, motorcycles, bicycles, or pedestrians, pedestrian accidents, collisions with fixed objects, or vehicle overturns. The project is crucial due to the significant impact of road traffic accidents on the safety of city residents and visitors, as well as on road infrastructure and emergency services. Reducing mortality rates related to road traffic accidents is a key goal for improving road safety in the city. The Mobility and Road Safety Observatory (OMSV), under the Transportation Secretariat of the Autonomous City of Buenos Aires, has requested the development of a data analysis project to provide information for local authorities to take measures to reduce fatalities in road traffic accidents.

## Data Preparation
For the project's initiation, the data preparation and transformation (ETL) process involved converting the provided Excel data into CSV format, creating two separate files: "Homicides" and "Victims." While most of the data was clean, a major challenge was finding a suitable API to retrieve accurate weather information for Argentina.

## Exploratory Data Analysis (EDA)
The EDA process began with a general numerical analysis, examining basic statistical figures to understand the data better. A distribution analysis followed to identify patterns and outliers in accident frequencies and locations. A detailed correlation analysis explored relationships between various factors, including time, geography, and vehicle types. It's important to note that while efforts were made to find correlations with weather conditions, this proved challenging as there were likely multiple factors at play, and most of the correlations with weather were found to be minuscule. The team then experimented with different graphical representations to select effective visualizations for the Power BI dashboard.

## Key Performance Indicators (KPIs)
Three key performance indicators (KPIs) were defined to measure the project's impact:
1. **KPI 1: Homicide Rate Reduction**
   - Goal: Reduce the rate of homicides in traffic accidents by 10% in the last six months in CABA (Ciudad Autónoma de Buenos Aires).
2. **KPI 2: Fatal Motorcycle Accident Reduction**
   - Goal: Reduce the number of fatal motorcycle accidents by 7% in the last year in CABA.
3. **KPI 3: Nighttime Traffic Accident Reduction**
   - Goal: Achieve a 5% reduction in the rate of nighttime traffic accidents in CABA.

## Power BI Dashboard
A comprehensive Power BI dashboard was created to visualize and analyze the data related to road safety in Argentina. The dashboard is designed to provide insights into various aspects of traffic accidents and the impact of the key performance indicators (KPIs). Below are the main components of the dashboard:
- **Main Page:** The main page serves as a general overview of accident reports and key statistics. It includes visualizations such as accident trends over the years, age distribution of victims, a heat map showing accident hotspots, and a fatality count. [Link to Main Page Image](#)

- **KPI Expositions:** Three separate pages are dedicated to explaining each key performance indicator (KPI) in detail. These pages provide a deep dive into the metrics used for KPI measurement and their relevance to road safety goals. [Link to KPI 1 Image](#) [Link to KPI 2 Image](#) [Link to KPI 3 Image](#)

- **Additional Resources:** In addition to the main components, the dashboard provides access to additional resources, including datasets, images, and workbooks used in the analysis. Stakeholders and collaborators can explore these resources to gain a deeper understanding of the project. [Link to Resources](#)

Feel free to click on the provided links to access images of each page of the Power BI dashboard and explore the visualizations and insights they offer.

## Resources
- [Link to Datasets](#): Access the datasets used in the analysis.
- [Link to Images](#): View images and visualizations generated during the project.
- [Link to Workbooks](#): Access workbooks and notebooks used for data analysis.

Stakeholders and collaborators are encouraged to explore the project and utilize the provided resources to gain insights into road safety in Argentina.
