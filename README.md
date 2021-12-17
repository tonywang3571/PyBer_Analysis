# PyBer_Analysis

## Overview of Project

**Purpose:**  
V. Isualize, the CEO of a ride sharing company called Pyber, has tasked us with analyzing data and creating visualizations from January to early May for the 2019 year. She was impressed with our initial analysis and has given Omar and I another assignment. The purpose of this analysis is to use Python and Pandas to create a new summary DataFrame and multiple-line graph that shows the total weekly fares for each city type.


## Resources:
- Data Source: city_data.csv, ride_data.csv
- Software: Python 3.9.7, Anaconda 4.10.3, Jupyter Notebook 6.4.5

## Analysis and Results

**Analysis:**  
For this analysis, we were provided with a dataset for city data and a dataset for ride data. The city information had information on city name, the number of drivers in the particular city, and the city type(urban, suburban, rural). The ride dataset has information on the city name, date and time of the rides, the fare or cost of the ride, and the ride ID. Looking at our datasets, city name was one data that they both had in common, so we were able to combine them through the city name. From there, we performed calculations to find the total rides, total drivers, and total fare for each city type. This information was then used to calculate the average fare per ride and the average fare per driver. Then we were able to join all of the calculations into a new summary dataframe.  

The next item on our analysis involves us creating a multi-line graph for total weekly fares by each city type. Going back to our combined dataset, we were able to use a method called 'pivot', which is similar to creating a pivot table in Excel, to essentially create a pivot table within Jupyter Notebook. We resampled the data into weeks, then we created the graph that V. Isualize asked us to create.


**Results:**  
From our analysis, we can see that there are differences in values between the different city types of our data. Though rural areas have the least number of total rides and drivers, but they yield higher average fare per ride and average fare per driver when compared to suburban and urban city types. Part of why the average fare per ride and per driver is higher in rural areas could be because rural areas are more spread out and require longer travel times between destinations, which would increase the fare of each ride when compared to suburban or urban areas. The same could be true for why there might be lower total rides and total drivers because the distance between destinations are further, thus would increase the fare for each ride and people would shy away from taking Pyber due to the higher cost of the ride. This could also be a contributor to less drivers overall. On the other hand, when we look at urban city types, we can see that there is over 10x increase in number of rides compared to rural city type. We know that urban city types are more population dense compared to rural areas, therefore it makes sense on why the total number of rides are higher. Average fare per ride and per driver are lower potentially because the consumer's destination is not as far away compared to a consumer's destination in a rural area (with other factors considered equal). Looking at the multi-line graph, we can see from January to end of April, the overall revenue of our services comes from urban areas and not so much from rural areas. Even though there are higher averages per ride and per driver from rural areas, but because there are more rides in the urban areas, it allows higher efficiency of the drivers. Meaning that if we have a driver in an urban area, they might be giving rides one after another with minimal wait time between consumers. As opposed to a rural area, where the wait time between consumer is higher.
<img src="Resources/Summary_df.PNG">  
<img src="Analysis/Pyber_fare_summary.PNG">  

## Challenge Summary

**Summary**  
(3 BUSINESS RECCOMMENDATIONS TO CEO)


### Codes Used  
<img src="Resources/Code1.PNG">  
<img src="Resources/Code2.PNG">  
<img src="Resources/Code3.PNG">  
<img src="Resources/Code4.PNG">  
<img src="Resources/Code5.PNG">  
<img src="Resources/Code6.PNG">  
<img src="Resources/Code7.PNG">  
<img src="Resources/Code8.PNG">  
<img src="Resources/Code9.PNG">  
<img src="Resources/Code10.PNG">  
<img src="Resources/Code11.PNG">  