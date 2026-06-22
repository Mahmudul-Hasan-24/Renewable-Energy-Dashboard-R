# Renewable Energy Consumption Dashboard

> Interactive R dashboard analyzing global renewable energy trends 
> across countries and years — built with R, ggplot2, and Shiny-ready 
> visualizations including maps, scatter plots, and time series charts.

## Project Overview
Designed and built an interactive data dashboard to explore global 
renewable energy consumption patterns. The dashboard enables users to 
filter by country and year, compare energy sources, and identify regional 
trends through multiple chart types.

**Tools:** R · ggplot2 · dplyr · tidyr · readr · rpart

## Dashboard Features
- Interactive choropleth map — select any variable to visualize 
  geographically across countries
- Time series charts — track renewable energy trends over time 
  per country or region
- Scatter plots — explore relationships between energy variables
- Filters — drill down by year and country dynamically

## Key Insights
- Identified regional leaders and laggards in renewable energy adoption
- Revealed growth trends in solar and wind energy across EU countries
- Highlighted correlation between GDP and renewable energy investment

## Data
Source: `df_countries_preprocessed.csv` — preprocessed country-level 
energy consumption data

## How to Run
```r
install.packages(c("dplyr","ggplot2","rpart","rpart.plot",
                   "readr","tidyr","lubridate"))
source("R/analysis_script.R")
```

## Skills Demonstrated
Data wrangling · Interactive visualization · Dashboard design · 
Geospatial analysis · Stakeholder communication



## Author

**Mahmudul Hasan,Benjamin, Jürgen**
M.Sc. Computational Social Systems (Business Analytics)
Technical University of Graz & University of Graz
[LinkedIn](https://www.linkedin.com/in/mahmudul-hasan-764307249/) · [GitHub](https://github.com/Mahmudul-Hasan-24)
