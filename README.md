# PyBer_Analysis

## Project Overview
A newly-hired data analyst's first assignment at PyBer, a ride-sharing app company, was an exploratory analysis of ride-sharing data from January to early May 2019 using Python and Pandas.  This project features the CEO's follow-on assignment to the new-hire data analyst: to generate a summary DataFrame of the ride-sharing data by city type and then to construct a multiple-line graph using Matplotlib displaying the total weekly fares for each city type.  The purpose of this project is to help PyBer improve access to ride sharing services and to determine affordability for under-served neighborhoods.

## Resources
- Data Source: city_data.csv, ride_data.csv
- Software: Python 3.7.6, Visual Studio Code, 1.68.1
- Applications: Pandas libraries, Matplotlib, Jupyter Notebook

## PyBer Analysis Results
The analysis of the ride-sharing data yielded the following outputs:

![summary_DataFrame](https://github.com/mewers2/PyBer_Analysis/blob/main/Analysis/summary_DataFrame.png)

![PyBer_fare_summary](https://github.com/mewers2/PyBer_Analysis/tree/main/Analysis)

The three different types of cities produce very differing results when the ride, fare, and driver data were summarized.  

### Rural Cities Results
The rural cities have far less rides and drivers than the other city types and the total fares from the rural cities is the least of the the three city types.  However, the average fare per ride and average fare per driver is highest in the rural cities.  

### Suburban Cities Results
The suburban cities marketshare produce substantially higher total fares than the rural cities and the total rides and total drivers counts in the suburban cities are much higher than the rural cities.  But, the average fare per ride and average fare per driver in the suburban cities is less than in the rural cities.

### Urban Cities Results
The urban cities are the most lucrative city type generating by far the most fares revenue, as evidenced by the total fares displayed in the summary DataFrame and the urban city line on the line graph.  The urban city type also has the most rides taking place and the most drivers.  Lastly, the average fare per ride and the average fare per driver is lowest in the cities.

## PyBer Analysis Summary
Based on the analysis results from the ride-share data, three business recommendations that may help Pyber achieve their goals of improving access to ride sharing services and addressing affordability for under-served neighborhoods:
- Where possible, decrease fare rates in the rural areas in order to increase total ride counts for the rural cities and increase access to that under-served marketshare.
- As able, slightly increase ride fare rates in the urban cities.  This will offset the above recommended fare discounts in the rural cities and will help retain drivers in the urban cities, as it will increase the average fare per ride and average fare per driver for the urban cities.
- Increase the number of drivers available in the rural cities in an effort to increase the total rides count in the rural cities and provide greater access to ride sharing services.