# PyBer_Analysis
Analyze rideshare data from January 2019 to early May 2019 and create a compelling visualization for the CEO.

## Resources
city_data.csv
PyBer_ride_data.csv
ride_data.csv

## Overview
1. Import your data into a Pandas DataFrame.
2. Merge your DataFrames.
3. Create a bubble chart that showcases the average fare versus the total number of rides with bubble size based on the total number of drivers for each city type, including urban, suburban, and rural.
4. Create a bubble chart that showcases the average fare versus the total number of rides with bubble size based on the total number of drivers for three city types.
5. Determine the mean, median, and mode for the following:
	- The total number of rides for each city type.
	- The average fares for each city type.
	- The total number of drivers for each city type.
6. Create box-and-whisker plots that visualize each of the following to determine if there are any outliers:
	- The number of rides for each city type.
	- The fares for each city type.
	- The number of drivers for each city type.
7. Create a pie chart that visualizes each of the following data for each city type:
	- The percent of total fares.
	- The percent of total rides.
	- The percent of total drivers.

# Challenge

## Resources



## Overview

Create an overall snapshot of the ride-sharing data. In addition to your scatter and pie charts, she would like to see a summary table of key metrics of the ride-sharing data by city type, and a multiple-line graph that shows the average fare for each week by each city type.

## Part 1 Instructions

1. Create a PyBer Summary DataFrame.
2. Create a summary DataFrame that showcases the following for each city type:

- Total Rides
- Total Drivers
- Total Fares
- Average Fare per Ride
- Average Fare per Driver


### Summary of Dataframe

This dataframe is telling us:

1. There are fewer rides in the rural cities with the highest average fares and the least number of drivers.
2. There are more rides in the suburban cities with lower average fares than rural cities and almost 6 times the number of drivers.
3. The most rides are in the urban cities with the lowest average fares and over 30 times the number of drivers in the rural cities.

In conclusion, 

1.On average, rural drivers are making more per ride but because there are providing less rides they are making les than drivers in the other two cities.
2. Urban cities generate more overall income for the PyBer company because they have more rides.
3. Even though Suburban cities drivers are providing less than half the number of rides in the Urban cities, there are quite a few less drivers, so Suburban drivers are most likely to be making more than any of the other drivers because the total fares in the Suburban cities is only $566.36 less than half the total fares in the Urban cities.


## Part 2 Instructions

Create a Multiple-Line Plot for the Sum of the Fares for Each City Type.

- Plot the sum of the fares for each city type so that your final line chart:


- Create a pivot table:

### Summary of Multiple-Line Graph

The three city type on one graph make it easy to see which city types generate the most income throughout the time period specified.  It is clear the Urban cities generate the most income and the Rural cities the least.  You can also see the peaks and dips in income relative to the time of year.
