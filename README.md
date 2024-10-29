# Temperature Analysis and Visualization

This repository contains Python code for analyzing temperature data from 2005 to 2015, visualizing record high and low temperatures, and mapping weather stations using the Folium library.

## Contents

- `temperature_analysis.ipynb`: Main script that performs temperature analysis and visualization.
- `temperature (1) (1) (1) (1).csv`: CSV file containing historical temperature data.
- `BinSize (1) (1) (1) (1).csv`: CSV file containing weather station data.

## Libraries Used

- `pandas`: For data manipulation and analysis.
- `matplotlib`: For plotting temperature trends.
- `numpy`: For numerical operations.
- `folium`: For creating interactive maps.

## Data Description

1. **Temperature Data**:
   - Contains daily temperature measurements (TMAX, TMIN) for the years 2005-2015.
   - The data is filtered to remove leap days and grouped by the day of the year to compute daily max and min temperatures.

2. **Station Data**:
   - Contains information about various weather stations, including their names and geographic coordinates.

## Key Features

- **Temperature Visualization**: 
  - Plots record high and low temperatures for the years 2005-2014, with overlay for 2015 to identify any broken records.
  
- **Temperature Summary**: 
  - Calculates and displays mean, min, and max temperatures for the year 2015.

- **Weather Station Mapping**: 
  - Maps the geographic locations of weather stations based on a specified hash ID, allowing for interactive exploration.
