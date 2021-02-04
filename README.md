<img src="https://news.blr.com/app/uploads/sites/2/2020/12/COVID19-vaccine.jpg">

<!-- Add buttons here -->
![Follow me at Twitter](https://img.shields.io/twitter/follow/NMashinchi?style=social)
![Follow me at Twitter](https://img.shields.io/twitter/follow/leggomymego?style=social)
![GitHub last commit](https://img.shields.io/github/last-commit/megano/vaccine)

# Covid-19 Vaccine Distribution
**Project Status: We are iterating on our modeling work around this use case**
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
This project aims to create **data visualizations and zip code prioritizations** to aid public health officials in deciding **where to distribute the COVID-19 vaccines** in California.  Also we analyze equity metrics to track distribution. We live in CA, so we're currently focused on our state but can run a similar analysis on any of the 50 US states. Please reach out to me via twtter if you think your state or county would be interested to learn more about this project.

## Source Data
[(Back to top)](#table-of-contents)
<br>
We use several data sources to visualize covid's cumulative impact on various counties in California including: census data, Healthy Places Index, and CCVI scores.
<br>
1. Covid 19 Data (Update frequency - Daily):
- Covid19 Confirmed Cases: https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_US.csv
- Covid19 Total Deaths: https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_deaths_US.csv
2. California Hospital Data by County (Update frequency - Daily):
- Hospital Data: https://data.ca.gov/dataset/529ac907-6ba1-4cb7-9aae-8966fc96aeef
3. California Population Data by County:
- Population Data: https://worldpopulationreview.com/us-counties/states/ca
4. California Geo JSON file for Folium choropleth map**:
- California Geo JSON Data: https://github.com/codeforamerica/click_that_hood/blob/master/public/data/california-counties.geojson

## Data Science Methods
[(Back to top)](#table-of-contents)
<br>
+ Data Collection 
+ Data Cleaning
+ Feature Engineering
+ Exploratory Data Analysis
+ Data Visualization

## ML Technologies:
[(Back to top)](#table-of-contents)
<br>
+ Dev Env -> Google Colab / Jupyter Notebook
+ Languages/Libaries -> Python / Pandas / NumPy
+ Viz -> Matplotlib/ Seaborn/ Plotly
+ Other -> Folium/ Copy/ Json

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
+ Our notebooks visualize our findings, plotted on CA-state maps

## Installation:
[(Back to top)](#table-of-contents)
<br>
+ Clone this repo <a href="https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/cloning-a-repository" target="_blank">(for help see this tutorial).</a>
+ Raw data, data processing/transformation script is being kept in this repo. <a href="https://github.com/megano/vaccine/blob/main/prioritization_analysis.ipynb" target="_blank">Click here for notebook.</a>
+ **Note**: If GitHub doesn't load the notebook please refer to:
     + <a href="https://nbviewer.jupyter.org/github/megano/vaccine/blob/main/prioritization_analysis.ipynb" target="_blank">Jupyter Notebook Viewer - Full 
  Project</a>
     + <a href="https://nbviewer.jupyter.org/github/megano/vaccine/blob/main/prioritization_analysis_visuals.ipynb" target="_blank">Jupyter Notebook Viewer - Visuals</a>



