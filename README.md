# Global-Migration-Analysis

## Overview
This project analyzes global migration trends using data from the **Census Bureau's International Database API**, **International Migrant Stock Data from UN's Population Division**, and **ISO Country Codes Dataset**. The goal is to explore migration patterns, demographic influences, and their relationships to economic and social factors. It provides visualizations and insights into net migration rates (NMR), migration-to-population ratios, and the impact of age and gender on migration.

## Features
- **API Integration**: Fetches migration data for multiple years using the Census Bureau's API.
- **Exploratory Data Analysis (EDA)**: Includes a variety of analyses:
  - Migration trends by year and country.
  - Age and gender influences on migration.
  - Comparison of positive and negative NMR countries.
  - Correlation between migration and population size.
- **Interactive Visualizations**:
  - Line charts, scatter plots, heatmaps, and stacked bar charts.
 
## Data Source
The project uses data from the [Census Bureau's International Database](https://www.census.gov/programs-surveys/international-programs/about/idb.html), accessed via the API. The API provides population and migration data for various age groups and countries.

The project also uses data from [UN's Population division about International Migrant Stock Data](https://www.un.org/development/desa/pd/content/international-migrant-stock). This data gives information about the number of people migrated to each country over a period from 1990 - 2020 at 5-year regular intervals.

It also uses dataset of [ISO Country codes from Luke's GitHub Repo](https://www.un.org/development/desa/pd/content/international-migrant-stock). This dataset has been fetched from a GitHub repository of Luke Duncalfe who has created a list that are the result of merging data from two sources, the Wikipedia ISO 3166-1 article for alpha and numeric country codes, and the UN M49 Standard country or area codes for statistical use data for countries' regional, and sub-regional codes.

## Questions answered through this project (so far):
1. Which countries experience the highest & lowest Net Migration Rate?
2. How does Net Migration Rate change over time?
3. How does the Migration - to Population ratio vary across the countries?​
4. How does migration vary by age group across countries?
5. Do men or women migrate more, and how does this trend differ by region?
6. Which countries have higher Foreign-Born population migrants?
7. Which countries have higher Refugee Population?
8. How does population size impact migration?
9. What are the characteristics of countries with positive versus negative migration rates?

## Visualizations:
The project generates various visualizations, including:
- **Migration-to-Population Ratio vs. Population Size**:
  - Scatter plot with NMR categories (positive/negative).
- **Age Group Migration Trends**:
  - Stacked bar chart comparing migration trends across age groups.
- **Net Migration Rate Over Time**:
  - Line charts for countries with the most significant positive and negative NMR changes.
- **Choropleth Map**:
  - Global migration trends by country.
 
It is recommended to check out the ipynb notebook to get an in-depth overview of all the data cleaning steps taken and also to look at the visualizations and analysis carried out. 

## Key Findings
- Smaller countries like Qatar and UAE often have high migration-to-population ratios.
- Refugee-hosting countries like Lebanon experience significant migration challenges.
- Migration trends are influenced by age, with younger populations (e.g., 20-24) dominating migration flows.
- Positive NMR countries often correlate with higher economic opportunities and stability.



