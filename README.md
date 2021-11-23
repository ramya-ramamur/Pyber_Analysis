# Pyber Analysis

# Overview
An analysis of the ride-sharing data and total weekly fares for Pyber, a ride sharing company to summarize results on how data differs for Urban, Suburban and Rural city types. Our analysis will show the following:

  1. A ride-sharing summary by city type that will contain the following per city type : Urban, Suburban and Rural
  * Total Number of Rides
  * Total Number of Drivers
  * Total Fares
  * Average Fare per Ride
  * Average Fare per Driver
  2. A multiple-line chart of total fares for each city type: Urban, Suburban and Rural
  
### Resources
* Data Source: 
    1. City Data : city_data.csv
    2. Ride Data : ride_data.csv
* Software: Python 3.8.8, Pandas Dataframe

# Results
1. Ride Sharing Data Summary Table

<img width="614" alt="Ride_data_summary" src="https://user-images.githubusercontent.com/75961057/143137018-740ab602-d2d4-403e-9fa0-0b32019ee222.png">

From the above table, you can see that the number of rides, drivers, and totals fare is the highest for Urban afreas as compared to Suburban and Rural areas. Interestingly the average fare per ride and average fare per driver though is the highest in Rural areas. 

3. A multiple line plot that shows the total weekly of the fares for each type of city.
 
 ![PyBer_fare_summary](https://user-images.githubusercontent.com/75961057/143134754-e3844138-4be9-418f-900c-cea4f54f541e.png)

# Summary
1. There are approximately 0.5 rides per driver in Urban areas. Meaning the number of drivers is too many for the current level of rides. But, Urban areas also have most rides 1625 when compared to 125 in rural areas which shows that there is an increasing demand in Urban areas. The company should therefore increase advertising in Urban areas to improve ridership and revenue. 
2. The fares charged in Urban areas is ~$10 lesser than in Rural areas. An analysis has to be done on why this is so. Is it because in Rural areas, the distance traveled is more per ride than Urban areas or is Pyber charging less and can increase the cost per ride in Urban areas?
3. The line chart shows that between the months of March and April, the ridership for Urban areas is very volatile. Pyber needs to find out why this is happening so that they can address the sharp declines and increases in total fares in that month.  
