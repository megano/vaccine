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
<a href="https://github.com/megano/vaccine/blob/main/prioritization_analysis_visuals.ipynb" target="_blank">Jupyter Notebook Viewer - Visuals</a>

## Table of contents
- [Summary](#summary)
- [Problem](#problem)
- [Data](#data)
- [Methods Used](#methods-used)
- [Technologies](#technologies)
- [Project Description](#project-description)
- [Project Results](#project-results)
- [Installation](#installation)

## Summary
[(Back to top)](#table-of-contents)
<br>
This is a pro-bono project with the goal of creating data visualizations & zip code prioritizations to aid public health officials as they decide where & how to distribute the covid-19 vaccines & what equity metrics to use to track distribution. We're currently focused on CA, since that's where we live, but can run a similar analysis on any of the 50 US states. Reach out if you think your state or county would be interested. 

## Problem
[(Back to top)](#table-of-contents)
<br>
State Public Health Officials are tackling unprescidented logistical, financial and trust challenges in distributing the covid-19 vaccine in addition to racial and ethnic disparities. 

## Data
[(Back to top)](#table-of-contents)
<br>
We use several data sources to visualize covid's cumulative impact on various counties in California including: census data, Healthy Places Index, and CCVI scores.
<br>
**Covid 19 Data (Update frequency - Daily):**
+ Covid19 Confirmed Cases: https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_US.csv
+ Covid19 Total Deaths: https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_deaths_US.csv
<br>
**California Hospital Data by County (Update frequency - Daily):**
+ https://data.ca.gov/dataset/529ac907-6ba1-4cb7-9aae-8966fc96aeef
<br>
**California Population Data by County:**
+ https://worldpopulationreview.com/us-counties/states/ca
<br>
**California Geo JSON file for Folium choropleth map**:
+ https://github.com/codeforamerica/click_that_hood/blob/master/public/data/california-counties.geojson

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
     + <a href="https://github.com/megano/vaccine/blob/main/prioritization_analysis_visuals.ipynb" target="_blank">Jupyter Notebook Viewer - Visuals</a>
## 
![Various Plots](https://github.com/megano/vaccine/blob/main/images/covid-deaths-proportional-county-map.png "Covid Deaths County Map")



