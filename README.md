# Ride-Share Data Analysis
Project using Pandas and Jupyter Notebook to analyze, format, and display ride share data for the PyBer app.

## Table of contents
* [Overview of Project](#overview-of-project)
* [Resources](#resources)
* [PyBer Results](#pyber-results)
* [Summary](#summary)

## Overview of Project
I assisted in analyzing large datasets from CSVs for a ride-sharing app called PyBer. We showcased the relationship between types of cities, number of drivers, number of riders, and fares. These visualizations will be used to improve access to PyBer services and determine affordability for underserved neighborhoods. 

### Resources
- Data source: city_data.csv, ride_data.csv, PyBer_ride_data.csv
- Software: Anaconda 2021.11, Python 3.7.11, Jupyter Notebook

## PyBer Results
Our first visualization was a scatterplot showing total rides and average fares in the different city types:

<p align="center">
  <img src="https://github.com/kolemae/Pyber_Analysis/blob/main/Analysis/Fig1.png">
</p>

At a glance, we can see that while urban cities had lower average fares, they had significantly more rides. This is shown again in box-and-whisker plots ([Fig2](/Analysis/Fig2.png), [Fig3](/Analysis/Fig3.png)) and pie charts ([Fig5](/Analysis/Fig5.png), [Fig6](/Analysis/Fig6.png)).

<p align="center">
  <img src="https://github.com/kolemae/Pyber_Analysis/blob/main/Analysis/Fig4.png">
</p>

Urban cities also had the highest number of drivers, with 2405, 490, and 78 drivers in urban, suburban, and rural cities respectively. This can also be seen in [Fig7](/Analysis/Fig7.png).

<p align="center">
  <img src="https://github.com/kolemae/Pyber_Analysis/blob/main/Analysis/PyBer_summary.png">
</p>

Seen in the PyBer Summary DataFrame, as far as fares go, rural city drivers are taking the lead. However, the rest of the data suggests PyBer is overall more accessible and affordable in urban cities. 

<p align="center">
  <img src="https://github.com/kolemae/Pyber_Analysis/blob/main/Analysis/Fig8.png">
</p>

The final visualization shows weekly total fare changes in the different city types for the first 4 months of 2019. Urban cities take in the most in total fares, followed by suburban and rural cities. There appears to be a similar peak time, at the end of February, for all city types.

## Summary
Based on this analysis I suggested that the PyBer CEO:

1. Improves accessibility and affordability of PyBer in rural cities to encourage growth of use
2. Address wage disparity for drivers depending on city type so drivers aren't discouraged by low average fare per driver in urban cities
3. Increase drivers available in suburban and rural areas to better serve riders

Other data to look into for further decision making would be the average distance of rides for city types, wait times for rides, and the peak times for total fares and what may affect them.
