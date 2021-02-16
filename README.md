<img src="https://news.blr.com/app/uploads/sites/2/2020/12/COVID19-vaccine.jpg">

<!-- Add buttons here -->
![Follow me at Twitter](https://img.shields.io/twitter/follow/NMashinchi?style=social)
![Follow me at Twitter](https://img.shields.io/twitter/follow/leggomymego?style=social)
![GitHub last commit](https://img.shields.io/github/last-commit/megano/vaccine)

# Covid-19 Vaccine Distribution
**Project Status: In progress**
<br>
<a href="https://nbviewer.jupyter.org/github/megano/vaccine/blob/main/prioritization_analysis.ipynb" target="_blank">Jupyter Notebook Viewer - Full Project</a>
<br>
<a href="https://nbviewer.jupyter.org/github/megano/vaccine/blob/main/prioritization_analysis_visuals.ipynb" target="_blank">Jupyter Notebook Viewer - Visuals</a>

## Table of contents
- [Project Objective](#summary)
- [Data](#data)
- [Methods Used](#methods-used)
- [Technologies](#technologies)
- [Project Description](#project-description)
- [Project Results](#project-results)
- [Installation](#installation)

## Project Objective
[(Back to top)](#table-of-contents)
<br>
This project aims to create data visualizations and zip code prioritizations to aid public health officials in deciding where and how to distribute the covid-19 vaccines and what equity metrics to use to track distribution. Since that's where we live, we're currently focused on California but can run a similar analysis on any of the 50 US states. Please reach out if you think your state or county would be interested to learn more about this project.

## Data Sources 
[(Back to top)](#table-of-contents)
<br>
**Covid19 Data:**
+ <a href="https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_US.csv" target="_blank">Covid19 Confirmed Cases by Johns Hopkins CSSE (Update frequency - Daily (scoped to CA))</a>
+ <a href="https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_deaths_US.csv" target="_blank">Covid19 Total Deaths by Johns Hopkins CSSE (Update frequency - Daily (scoped to CA))</a>

**California State Data:**
+ <a href="https://data.ca.gov/dataset/529ac907-6ba1-4cb7-9aae-8966fc96aeef" target="_blank">Hospital Data by County (Update frequency - Daily) from CA.gov</a>
+ <a href="https://worldpopulationreview.com/us-counties/states/ca" target="_blank">Population Data by Country from worldpopulationreview.com</a>
+ <a href="https://github.com/codeforamerica/click_that_hood/blob/master/public/data/california-counties.geojson" target="_blank">California GeoJSON file for Folium choropleth map from Code for America</a>

**Socioeconomic / Health Metrics:**
+ <a href="https://healthyplacesindex.org/data-reports/" target="_blank">California Healthy Places Index (HPI) combined CSV called HPI2_MasterFile from 2019-04-24. Source: healthyplacesindex.org</a>
+ <a href="https://www.google.com/url?q=https://covid-static-assets.s3.amazonaws.com/US-CCVI/ccvi-US.xlsx&sa=D&source=editors&ust=1613440006571000&usg=AOvVaw2nplFz4KgkS4-GgiP6J3_3" target="_blank">Covid Community Vulnerability Index (CCVI) score developed by Surgo Ventures</a>

## Methods Used
[(Back to top)](#table-of-contents)
<br>
+ Data Collection 
+ Data Cleaning
+ Feature Engineering
+ Exploratory Data Analysis
+ Data Visualization

## Technologies:
[(Back to top)](#table-of-contents)
<br>
+ Google Colab
+ Jupyter Notebook
+ Python
+ Pandas
+ NumPy
+ Matplotlib
+ Seaborn 
+ Plotly
+ Folium
+ Copy
+ Json

## Project Description:
[(Back to top)](#table-of-contents)
<br>
+ We collected multiple datasets to conduct this analysis. We imported Covid19, Hospital, Healthyplaceindex, and Population data. 
+ We cleaned our data by using Pandas and filtered all the information down to California's 58 counties. For two counties, such as Alpine and Sierra, the California government didn't provide any hospital information. As a result, we decided to set the value to zero. 
+ Regarding feature engineering, we converted the data type from object to  DateTime, created columns such as the total covid cases and deaths for each county per 100,000 people, percentage of deaths based on total cases, etc.
+ For our visuals, we primarily focused on using Seaborn, Plotly, and Folium. We had to incorporate a Geo JSON file for the Folium choropleth maps to get the county's correct layers. 

## Project Results:
[(Back to top)](#table-of-contents)
<br>

## Installation:
[(Back to top)](#table-of-contents)
<br>
+ Clone this repo <a href="https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/cloning-a-repository" target="_blank">(for help see this tutorial).</a>
+ Raw data, data processing/transformation script is being kept in this repo. <a href="https://github.com/megano/vaccine/blob/main/prioritization_analysis.ipynb" target="_blank">Click here for notebook.</a>
+ **Note**: If GitHub doesn't load the notebook please refer to:
     + <a href="https://nbviewer.jupyter.org/github/megano/vaccine/blob/main/prioritization_analysis.ipynb" target="_blank">Jupyter Notebook Viewer - Full 
  Project</a>
     + <a href="https://nbviewer.jupyter.org/github/megano/vaccine/blob/main/prioritization_analysis_visuals.ipynb" target="_blank">Jupyter Notebook Viewer - Visuals</a>



