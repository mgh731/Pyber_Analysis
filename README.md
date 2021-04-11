# Pyber Analysis

## Overview of the analysis
Pyber is a ridesharing application that services three city types: Rural, Suburban, and Urban cities. Analysis was completed to be used to help make decisions that should improve access to the services and determine affordability for underserved neighborhoods. 

## Purpose of analysis
More specifically the analysis in this report summarizes ride-sharing data (number of drivers, fares, and dates) by city type. It includes a multiple-line graph displaying weekly fares by city type. Together the purpose of these assets is to show differences in the usage of Pyber ride-sharing app by city type. Analyzing performance indicators in this way will help Pyber make decisions about resources spent geographically that will achieve the goals all up.

## Results

### Noteable Summary Insights

**Summary Table:**

![Challenge_Fig0](/Resources/Challenge_Fig0.png)

There are several noteable statistics based on this table:
1. Though there are a lot less drivers in Rural cities compared to Suburban and Urban cities, drivers in Rural cities are more often to get a fare and are more likely to make higher fares than drivers in other types of cities. The high competition for drivers in this way makes it more profitable to be a driver in Rural areas. (Note: Missing from this set of numbers if the time spent per ride which could provide more insight)

2. The Average Fare per Ride between all three city types is within $10 of each other with Urban fares averaging expectedly less than Rural and Suburban. 

3. Total Fares from Urban cities are much higher than Suburban and Rural cities. But where the total rides increases from Suburban to Urban cities by 89%, the total fares difference is only 41% between Suburban and Urban. Compared to Rural rides and fares that increased by 133% and 107% respectively. 

  **Calculation:**
 > 89% -  (Suburban Total Rides + Urban Total Rides /2) / (Urban Total Rides - Suburban Total Rides) *100 
 
 > 41% -  (Suburban Total Fares + Urban Total Fares /2) / (Urban Total Fares - Suburban Total Fares) *100 
 
 ### Noteable Line Graph Insights
 **Summary line graph**:

![Challenge_Fig1](/Resources/Challenge_Fig1.png)
 
 This line graph also tells us important pieces of info related to time detail of the the data: 
 1. There are far more spikes in Urban Fares on a week-by-week basis. 
 
 2. There was a major spike among all city types one week at the end of February (potentially due to school break?) but most other weeks there are no correlation between the weeks.
 
# Summary recommendations
1. One of the company goals should be to increase rides in Rural cities, where the Average Fare per Ride is higher, the drivers more likely to be long-term (note: need additional data), and an increase in rides is more likely to affect the total fare $ compared to Suburban rides.

2. Given the spikes in fares (and rides) for Urban activity, company should consider opportunities to scale up and down operations in any places that are static. Examples: Number of support staff, Promotions, Driver incentives

3. Future analysis should be completed that answers questions like the following
    a. Type of destination by ride id
    b. Average income by city
    c. As mentioned, avg length of employment of driver by city type
    
