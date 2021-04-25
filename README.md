# **  WeatherPy

## *Project Overview*
Plan My tip is a top travel company that specializes in internet services for Hotels and Lodging services. Need to help Jack collect and present Data for customers via the search page which they will filter based on their preferred travel criteria to find their ideal hotel anywhere in the world. to perform this analysis and create our Itenery plan and maps we will use, Jupyter Notebook, Pandas Library, CitiPy, Python Requests, APIs, JSON.

 
                  
## *Analysis & Results*
### Analysis
To perform this task I will Use Jupyter Notebook and CitiPy Module to collect weather data from over 500 Cities over the world. Then I will perform requests on the Openweather Map API to retrieve the JSON weather data from these cities. this data will help the team to  Then The weather Data will be added to Pandas DataFrame using MatplotLib to create series of
scatter plots to show the relationship between Lattitied and a variety of weather parameters for over 500 cities around the world. as part of the analysis need to perform statistical calculations on the data using linear regression on the weather parameters in northern and southern Hampshire. This data will help the team predict the best time of the year for people to plan their vacations. Finally, we need to export the data clean it and use the weather data to use the best vacation based on certain weather criteria, and then map these cities on a map using Jupyetr gmap and google places API.  
         
### Results
1) from ride-sharing summary DataFrame by city type (Table_1 below), we conclude the following: as cities get more populated, we see an exponential increase in Total # of rides, Total # of Drivers & Total Fares. But this increase led to a significant drop in Average Fare per Driver and Average Fare per Ride. resulting in less revenue per Average Driver 
  1.1 Total Rides in Urban Cities is 2.6 X total rides in Suburban cities and 13X Total rides in rural Cities. Total Rides in Suburban cities is 5X vs. Rural Cities. 
  1.2 Total # of drivers increase significantly in Urban cities is ~31X (2405 Drivers)  vs. Rural cities ( 78 Drivers). Suburban cities Total drivers is ~6X vs. rural Cities.
  1.3 Total fares, didn't increase in the same ratio as total Drivers and Total Rides. in Urban cities the increase is only 9.2X vs. Rural cities and 2X vs. Suburban cities...
  1.4.  Average Fare Ride and Average Fare per Driver Dropped significantly, leading to the conclusion as cities get more populated # of drivers increases significantly, leading to more competition and an accelerated decrease in Fares and revenue per Driver.  

   ![summary table](https://user-images.githubusercontent.com/80013773/115135558-44209f00-9fce-11eb-8410-31a3a0a4d010.png)

2) Based on "Total Fare By City Type" (see chart below), we can conclude that:
  2.1 Total fares are not stable, and they fluctuate over time, within a minor uptrend. there is some level of correlation in trend between the 3 city types.  
  2.2 Urban Fare by City type is in run-rate of ~2000 to 2500 ( with two exception points) 
  2.3 Suburan Total Fare by City Type is in run-rate ~850 to ~1400 (with few outlier points) 
  2.4 Total Fare in Rural Cities in the run-rate of ~ 50 to 500.
 
   ![Challenge_fare_summary](https://user-images.githubusercontent.com/80013773/115135490-b5138700-9fcd-11eb-891b-5374179d3999.png)

    
## *Summary*
The out will give 3 Maps
1) weather serach map 
![WeatherPy_vacation_map](https://user-images.githubusercontent.com/80013773/116008822-5cdf1500-a5cb-11eb-8618-5489a9e79709.png)

2) Travel Map - Travel route 
![WeatherPy_travel_map](https://user-images.githubusercontent.com/80013773/116008930-a0d21a00-a5cb-11eb-94c5-8c9a0b9b8a91.png)

3) Travel Markers
![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/80013773/116010325-273e2a00-a5d3-11eb-8c1e-e3fc8fcba421.png)



### Advantages
 By writing code with  Jupyter Notebook, Pandas Library, CitiPy, Python Requests, APIs, JSON. is a powerful tool enabling the work with a large scale of Data and Plotting these Data into charts and Maps. using the API tool is helpful to retrieve information and plot Info. om Maps (using gmap and Google Places API)