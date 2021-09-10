# PyBer Analysis

In this week project we are going to analyze data for **PyBer** - a *ride-sharing app*- with the purpose of generating plots that helps to understand trends and relationships between total number of drivers, rides and fares by type of cities. From the analysis and plots, *PyBer* could take decisions that improve the access to ride-sharing services and determine affordability for underserved neighborhoods.

## Overview

After an initial analysis of the data, we need to create a ride-sharing table summarizing important information and a multiple-line graph of the total weekly fares along 4 months for each city type, which allows us to gather insights about the differences among the three city types: *Urban*, *Suburban*, and  *Rural*.  Pandas-Python in jupyter notebook was used for coding and creating the dataframe and the line chart plot (Here it is the [code](https://raw.githubusercontent.com/LeidyDoradoM/PyBerAnalysis_Challenge/main/PyBer_Challenge.ipynb)).  

## Results

Previous analysis showed us how rides and number of drivers vary depending on the type of city.  Now, we need a more detail information about how fares vary depending on the area or region where the rides take place.  Firt, we summarize the specific information into a data frame and then using **Matplotlib Library**, we create a line chart that shows how our relationship of interest is.

### PyBer Summary Data

In this analysis, three city types are considered: *Urban*, *Rural* and *Suburban*.  The dataframe created from the data provided for the App is shown in Table 1. We can see how the total of drivers and rides vary for the three types of cities considered. There are more drivers and rides in Urban cities than in Suburban or Rural.  The same pattern is followed by the total fares, which is undestandable, since there are more rides in Urban cities than in Rural cities.  On the contrary, the average fares per ride or dirver, are lower for Urban cities than Rural cities.  This is because, although the number of rides is higher in urban cities, the number of drivers also increases for urban cities, which means that the average does not neccesarily goes up.

![df](https://raw.githubusercontent.com/LeidyDoradoM/PyBerAnalysis_Challenge/main/analysis/df_pyberSummary.png)
Table 1. Ride-sharing data for: Rural, Suburban and Urban Cities.

### Total Weekly Fares for City Types

As well as in the dataframe shown in Table 1, the total fare over the four considered months (January 1/2019-April 30/2019) for Urban Cities is greater than the total fare for Suburban and rural cities. This trend can be seen in the below figure.

![image](https://raw.githubusercontent.com/LeidyDoradoM/PyBerAnalysis_Challenge/main/analysis/TotalFare_by_CityType.png)
Figure 1. Total Fares by City Type in a period of time of 4 months.

For each one of the three types of cities, the total fare fluctuate within a range of money over the considered period of time. However, there is not a constant in how these values change from week to week. In some weeks, the fare increases but for the next week, the fare decreases, so there is not a pattern or trend that could be valued over the time.

## Summary

According to the dataframe and line chart showed above, some conclusions can be derived and based on them, some marketing stategies could be considered in order to address the disparities of number of rides and drivers for the rural and suburban areas.

1. Enhance the portdolio of benefits and perks for people in Suburban and Rural areas, that want to work as drivers.

2. More advertisement for visibility of the app service in rural and suburban areas.

3. A marketing strategy to increase the number of users, this could be for example to offer discounts for first users, some periodically discounts for loyal customers, etc.

