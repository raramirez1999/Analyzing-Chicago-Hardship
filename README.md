# Analyzing Chicago Hardship
# Selected Socioeconomic Indicators Analysis for Chicago Communities

![Chicago Communities](https://upload.wikimedia.org/wikipedia/commons/thumb/9/98/Chicago_montage1.jpg/640px-Chicago_montage1.jpg)

## Introduction

The city of Chicago released a dataset of socioeconomic data containing six indicators of public health significance and a "hardship index" for each community area in Chicago for the years 2008 – 2012. This dataset provides valuable insights into the challenges faced by various communities in the city.

The Dataset was a basic skeleton project in the "IBM Databases and SQL for Data Science with Python course," I was inspired and wanted to develop further insights and utilize skills I've learned such as Pandas, SQLite, Matplotlib, and Seaborn to create further insights and employ exploratory data analysis to discover data-driven visualizations surrounding reasoning for hardship in Chicago communities.

## Dataset Description

The dataset comprises the following variables:

1. **Community Area Number (ca):** A unique identifier for each row of the dataset.
2. **Community Area Name (community_area_name):** The name of the region in the city of Chicago.
3. **Percent of Housing Crowded (percent_of_housing_crowded):** The percentage of occupied housing units with more than one person per room.
4. **Percent Households Below Poverty (percent_households_below_poverty):** The percentage of households living below the federal poverty line.
5. **Percent Aged 16+ Unemployed (percent_aged_16_unemployed):** The percentage of persons over the age of 16 years who are unemployed.
6. **Percent Aged 25+ without High School Diploma (percent_aged_25_without_high_school_diploma):** The percentage of persons over the age of 25 years without a high school education.
7. **Percent Aged Under 18 or Over 64 (percent_aged_under_18_or_over_64):** The percentage of the population under 18 or over 64 years of age (i.e., dependents).
8. **Per Capita Income (per_capita_income_):** Estimated community area per capita income calculated as the sum of tract-level aggregate incomes divided by the total population.
9. **Hardship Index (hardship_index):** A score that incorporates each of the six selected socioeconomic indicators. The hardship index ranges from 1 to 100, with a higher index indicating a greater level of hardship.

## Objective

The objective of this project is to analyze the socioeconomic indicators for different Chicago communities and explore the relationship between various factors and the hardship index.

## Project Setup

### Requirements

To run this project, ensure you have the following installed:

- [Jupyter Lab](https://jupyter.org/)
- [Python 3.x](https://www.python.org/)
- Libraries: pandas, matplotlib, seaborn

### Data Source

The dataset used in this analysis is obtained from the [Chicago City Portal](https://data.cityofchicago.org/resource/jcxq-k9xf.csv).

### Running the Analysis

Follow these steps to run the analysis:

1. Clone or download this repository to your local machine.
2. Open Jupyter Lab and navigate to the project directory.
3. Open the Jupyter notebook file `Chicago_Communities_Hardship_Analysis.ipynb`.
4. Execute the notebook cells to perform the analysis.

## Analysis Overview

The analysis consists of the following steps:

1. **Data Loading:** Connect to the SQLite database and load the dataset into the environment.
2. **Basic Data Exploration:** Perform basic SQL queries to get an initial understanding of the dataset.
3. **Identifying High Hardship Communities:** Identify communities with a hardship index above 50.
4. **Visualizations:** Explore the relationships between per capita income and hardship index, education level and hardship index, and unemployment rate and per capita income.

## Conclusion

By analyzing the selected socioeconomic indicators for Chicago communities, this project aims to gain insights into the hardship levels faced by different areas. The visualizations and data exploration can provide valuable information for policymakers and researchers working towards improving the living conditions in these communities.

Feel free to explore, contribute, or provide feedback to enhance this analysis. Happy analyzing!

![Chicago Skyline](https://upload.wikimedia.org/wikipedia/commons/thumb/e/eb/Chicago_sunrise_1.jpg/640px-Chicago_sunrise_1.jpg)
