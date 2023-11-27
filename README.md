# Meteorite Data Analysis Project

## Overview
This project involves the analysis of meteorite data from NASA to understand patterns, distributions, and correlations related to meteorite falls across different years, locations, and types. This analysis aims to delve into various aspects of meteorite occurrences, exploring factors such as location, time, meteorite classes, and potential correlations with precipitation.

## Project Objectives
- Clean and preprocess meteorite data, handling missing values and outliers.
- Visualize meteorite falls over time and by location using histograms and heatmaps.
- Estimate global meteorite fall counts using the USA as a reference.
- Investigate correlations between annual precipitation and recorded meteorite falls.

## Data Sources
- **Meteorite_DATA.csv:** Contains meteorite records with details like name, fall type, mass, year, coordinates, and geographical location.
- **Annual_precipitation_USA.csv:** Provides annual precipitation data for the USA.

## Libraries Used
- pandas
- numpy
- matplotlib
- geopandas
- cartopy


## Usage
1. **Data Preparation:** Clean the dataset, handling missing values, outliers, and refining data types.
2. **Visualization:** Plot histograms to display meteorite falls per year and decade, as well as heatmaps showing meteorite landings across the world and within the USA.
3. **Estimation:** Use land area comparisons to estimate global meteorite fall counts.
4. **Correlation Analysis:** Explore the relationship between annual precipitation and recorded meteorite falls.

## Findings
- Visualization reveals unexpected concentrations of meteorite falls in low population areas, challenging assumptions about sightings related to population density.
- Estimations based on USA data suggest a method to extrapolate global meteorite fall counts, utilizing land area ratios.
- Analysis indicates a mild negative correlation between annual precipitation and recorded meteorite falls, but the effect seems insignificant.


