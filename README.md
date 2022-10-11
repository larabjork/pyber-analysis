# Pyber Analysis
Data Bootcamp Challenge, Week 5

## Project Overview
This task involves examining ride-sharing data for three different types of cities, based on size: urban, suburban, and rural. Data are summarized in a Pandas DataFrame (tabular format) and then total weekly fares are plotted with Matplotlib in a multiple-line graph. This report summarizes differences among the city types that became apparent when examining the data, with the goal of informing decision-making at the parent company, Pyber.

## Results
Data analysis, completed in Jupyter Notebook using Pandas and Matplotlib, is available [here](https://github.com/larabjork/pyber-analysis/blob/main/PyBer_Challenge.ipynb)

Data sources are available here: 
[City data](https://github.com/larabjork/pyber-analysis/blob/main/Resources/city_data.csv)
[Ride data](https://github.com/larabjork/pyber-analysis/blob/main/Resources/ride_data.csv)

A summary of the data is shown below.

![dataframe showing summary of analysis](https://github.com/larabjork/pyber-analysis/blob/main/analysis/summary_data_frame.png)

### Total Rides by City Type
The number of rides appears to correlate with city type and therefore population size. The number of suburban rides is 5 times greater than the number of rural rides, and the number of urban rides is almost 3 times greater than the number of suburban rides and 13 times greater than the number of rural rides.

### Total Drivers by City Type
The number of drivers also appears to correlate with city type and therefore population size. The number of suburban drivers is 6.3 times greater than the number of rural drivers, and the number of urban drivers is 4.9 times greater than the number of suburban drivers and 31.8 times greater than the number of rural drivers.

### Total Fares by City Type for All Dates
Total fares follow a similar pattern to the total rides, not surprisingly. The total fares for suburban trips are 4.5 times greater than the total fares for rural trips, and the total fares of urban trips is 2.1 times greater than the total fares for suburban trips and 9.2 times greater than the total fares for rural trips.

### Average Fare per Ride by City Type
Average fares per ride are greatest among rural trips, followed by suburban and then urban trips. Rural riders are likely taking longer trips than their counterparts in other city types, meaning that they must pay more per ride.

### Average Fare per Driver by City Type
The pattern for average fares per driver is the same as for average fares per ride: greatest among rural trips, followed by suburban and then urban trips. Rural drivers are earning more per ride their counterparts in other city types.

### Total Fares by City Type for January through April 2019
A closer look at four months of data for total fares by city type is presented below.
![line chart showing 2019 data by city type](https://github.com/larabjork/pyber-analysis/blob/main/analysis/PyBer_fare_summary.png)

As shown in this chart:
* There is some variation in total fares within each type of city over this time period, but for a given city type, the variation is not too dramatic.
* In late February and early March, all cities show a roughly similar pattern of higher use dropping off, perhaps due to weather. This is worthy of further investigation.

## Summary
Pyber's commitment to transportation equity is most challenged in rural areas. On one hand, drivers in rural areas are able to earn more per ride, which is good for the drivers. On the other hand, rural riders must pay more per ride, which may be a limiting factor in their use of Pyber services. Pyber should consider exploring partnerships with local government/social service agencies to see if there are subsidy programs that could ease the burden on riders.

A closer look at other transportation options available in each city type could be instructive. It is most likely that urban residents have the most options, and understanding the competition in larger cities is key to building Pyber's market share in these environments.

As noted in the January through April data, an examination of weather patterns versus ride frequency could be instructive. Are riders more likely to use Pyber services if the weather is cold and/or rainy? Are drivers less likely to drive in these conditions? Knowing more about behavior could help Pyber adjust strategy in driver recruitment and rider advertising.

