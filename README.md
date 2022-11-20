# PyBer Analysis

## Overview

The purpose of this analysis is to summarize rideshare data by city type for PyBer. I started with 2 initial datasets in the form of .csv files. One dataset was city data which contained city, driver count, and city type (rural, urban, or suburban) and the other dataset was ride data which contained city, date, fare, and ride ID. I then merged the two datasets on city and performed calculations to determine the total rides by city type, total drivers by city type, total fare by city type, average fare per ride by city type, and average fare per driver by city type. After performing these calculations, I found the total sum of fares grouped by city type and by date and then used this final dataset to chart the total fare by city type.

## Results

![PyBer](https://user-images.githubusercontent.com/115508658/202929768-57a0d8e8-a8ec-4559-8472-58ef663469c8.png)

* In urban cities, total rides, total drivers, and total fares are highest while average fare per ride and average fare per driver is lowest
* Total rides in urban cities is 13 times higher than rural cities and 2.6 times higher than suburban cities
* Total drivers in urban cities is 30.8 times higher than rural cities and 4.9 times higher than suburban cities
* Total fares in urban cities is 9.2 times higher than rural cities and 2.1 times higher than suburban cities
* Average fare per ride in urban cities is 1.4 times lower than rural cities and 1.3 times lower than suburban cities
* Average fare per driver in urban cities is 3.3 times lower than rural cities and 2.4 times lower than suburban cities

![PyBer_fare_summary](https://user-images.githubusercontent.com/115508658/202929765-e4af446b-4525-4f6b-bf59-671616debc25.png)

* Over time, the total fare by city type is pretty steady, without any major increases or decreases
* Urban cities produce the most revenue, followed by suburban cities and then rural cities

## Summary

Recommendations for the CEO of PyBer:

1.	It could be beneficial to look at the total fare by city type over a whole year rather than only the first quarter. This could show if there are any seasonal up or down ticks that could be addressed by offering promotions to incentivize people to use PyBer.
2.	The average fare per ride is significantly higher in rural cities. With this dataset, it cannot be determined if this is due to longer trips or higher rates. It could be beneficial to include trip length (either in miles or minutes) in the analysis so that fare per mile or fare per minute could be calculated for all three city groups. If this analysis were performed and it was found that the fare rate is disproportionate for any of the city groups, the fare rate could be adjusted to be in line with the other groups. If the fare rate is higher in rural cities, this could deter customers in rural cities from using PyBer.
3.	The total number of drivers in urban cities is higher than the total rides. Additionally, urban cities produce the most revenue.  It would be beneficial to increase advertising or promotional offers in urban cities to increase the total rides. The benefits of this would be increased revenue, as well as assuring that more drivers have opportunities to accept trips from customers and earn an income.
