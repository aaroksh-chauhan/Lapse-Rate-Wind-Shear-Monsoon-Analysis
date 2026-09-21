# Lapse Rate and Wind Shear Analysis during the Monsoon

## Overview
This project analyzes atmospheric lapse rate, vertical temperature structure, 
and wind shear over a location in northern India, to understand vertical 
atmospheric behavior during the monsoon season.

## Objective
- Compute the lapse rate (the rate at which temperature drops with height) 
  between the 850 hPa and 500 hPa pressure levels
- Plot the vertical temperature profile and track how the lapse rate varies 
  over time during the monsoon season
- Compute wind shear (the difference in wind between 200 hPa and 850 hPa) as 
  a multi-year (1991–2021) climatological time series
- Derive specific humidity from relative humidity data for the same location 
  during the monsoon period

## Data
- **Source:** Gridded atmospheric reanalysis data (temperature, wind, and 
  relative humidity at multiple pressure levels)
- **Region:** A location in northern India (approx. 28–29°N, 76.8–77.3°E)
- **Time period:** Monsoon season analysis, with wind shear computed as a 
  climatology spanning 1991–2021

## Tools & Methods
- **Language:** Python
- **Key libraries:** xarray, numpy, matplotlib
- **Method:** Computed the lapse rate between 850 hPa and 500 hPa from 
  gridded temperature data, plotted the vertical temperature profile and a 
  time series of lapse rate variation during the monsoon, calculated wind 
  shear between 200 hPa and 850 hPa as a 30-year (1991–2021) climatology, and 
  derived specific humidity from relative humidity and temperature data

## Results

- The vertical temperature profile showed the expected decrease in 
  temperature with height between the lower and mid-troposphere
- Lapse rate varied over the course of the monsoon season, reflecting changes 
  in atmospheric stability
- Wind shear climatology (1991–2021) showed the characteristic monsoon wind 
  pattern between upper and lower levels

## Skills Demonstrated
- Atmospheric vertical structure analysis (lapse rate, temperature profiles)
- Wind shear and climatological time series analysis
- Working with multi-level, multi-decadal gridded reanalysis data
- Scientific visualization using Python

## Author
Aaroksh Chauhan — M.Sc. Atmospheric and Oceanic Sciences, IIT Bhubaneswar
