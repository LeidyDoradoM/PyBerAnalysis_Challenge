# PyBer Analysis

In this week project we will analyze data for **PyBer** - a *ride-sharing app*- with the purpose of generating plots that help to understand trends and relationships between total number of drivers, rides and fares by type of cities. From the analysis, *PyBer* people could take decisions to improve the access to ride-sharing services and determine affordability for underserved neighborhoods.

## Overview

After an initial analysis of the data, we need to create a ride-sharing table summarizing information about drivers, rides and fares for three different types of cities: *Rural*, *Suburban*, and *Urban*; and also a multiple-line graph showig how fares vary over a period of time of 4 months - from January to April- for each one of the considered city types.  Pandas-Python in jupyter notebook was used for coding and creating the dataframe and the line chart plot (Here it is the [code](https://github.com/LeidyDoradoM/PyBerAnalysis_Challenge/blob/main/PyBer_Challenge.ipynb)).  

## Results

Previous analysis showed us how rides and number of drivers vary depending on the type of city.  Now, we need a more detail information about how fares vary depending on the area or region where the rides take place.  First, we summarize the specific information into a data frame and then using **Matplotlib Library**, we create a line chart that shows how the relationship between the variables considered is.

### PyBer Summary Data

In this analysis, three city types are considered: *Urban*, *Rural* and *Suburban*.  The dataframe created from the data provided for the App is shown in Table 1. We can see how the total of drivers and rides vary for the types of cities considered. There are more drivers and rides in Urban cities than in Suburban or Rural.  The same pattern is followed by the total fares, which is evident, since there are more rides in Urban cities than in Rural cities.  On the contrary, the average fares per ride or driver, are lower for Urban cities than Rural cities.  This is because, although the number of rides is higher in urban cities, the number of drivers also increases for urban cities, which means that the average does not neccesarily go up.

![df](https://raw.githubusercontent.com/LeidyDoradoM/PyBerAnalysis_Challenge/main/analysis/df_pyberSummary.png)
Table 1. Ride-sharing data for: Rural, Suburban and Urban Cities.

### Total Weekly Fares for City Types

As well as in the dataframe shown in Table 1, the total fare over the four considered months (January 1/2019-April 30/2019) for Urban Cities is greater than the total fare for Suburban and rural cities. This trend can be seen in the below figure.

![image](https://raw.githubusercontent.com/LeidyDoradoM/PyBerAnalysis_Challenge/main/analysis/TotalFare_by_CityType.png)
Figure 1. Total Fares by City Type in a period of time of 4 months.

For each one of the three types of cities, the total fare fluctuate within a range of money over the considered period of time. However, there is not a constant variation in how these values change from week to week. In some weeks, the fare increases but for the next week, the fare decreases, so there is not a pattern or trend that could be kept over the time.

## Summary

The dataframe and line chart presented in Table 1 and Figure 1 show disparities in the number of rides and drivers for the rural and suburban areas respect to the Urban.  As well as, their differences regarding the fare is also huge for the Urban areas and Rural/Suburban.  The Urban total fare is almost ten times the Rural and twice the Suburban total fare.  If **PyBer** wants to improve the service they are offering and at the same time increase the revenues; they should consider some marketing, business strategies.  Below there are some recommendations for trying to level up some of the disparities mentioned before:

1. *More and appealing benefits for employers*. Enhance the portfolio of benefits and perks for the drivers in Suburban and Rural areas, so they are more willing to increase their time they work as drivers.  As well as, the new portfolio should include benefits that help to boost the hiring rates. This strategy would help to reduce the disparity in drivers.

2. *More advertisement*.  Invest in more aggressive advertising campaigns to increase the exposure of the brand, **PyBer App*, and reach more people, both customers and drivers. This has the potential to reduce the disparity in rides but also in drivers.

3. *Discounts for Customers*. A marketing strategy to increase the number of customers, especially in rural areas.  For example, offer discounts for first users, some periodically discounts for loyal customers, etc.