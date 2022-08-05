# PyBer_Analysis

## Analysis Overview

For this project we worked alongside Pyber, a ride-sharing app company valued at $2.3 billion. We performed an exploratory analysis of all the rideshare data from January to early May of 2019 to showchase the relationship between the type of city, and the number of drivers and riders, as well as the percentage of total fares, riders and drivers by type of city. 

Now we will present the final analysis requested by the company which consists of a summary of the ride-sharing data by city type and a multiple-line graph that shows the total weekly fares for each city type. The analysis will help PyBer improve access to ride-sharing services and determine affordability for underserved neighborhoods.

## Resources
- Data Source: city_data.csv, ride_data.csv
- Software:  Python 3.6.1, Jupyter Notebook, Pandas, Matplotlib

## Results

### Summary DataFrame Analysis

<img width="621" alt="PyBer_summary_df" src="https://user-images.githubusercontent.com/107893200/182993011-1dcbb671-dbd2-4154-8bc5-7101e0a86443.png">

#### Total Rides
From the information we obtained after filtering the data base by city we can see that the type of city with the most rides is Urban with 1,625 number of total rides, followed by Suburban with 625 total rides. At the end its located Rural with 125 total rides. We can see that between Urban and Rural category there is a difference of 1,500 rides.

#### Total Drivers
One of the reasons why there can be such a difference in total rides between one type of city and another is the number of drivers registered in each category. While Urban city type has a total of 2,405 drivers, Suburban has only 490 total drivers. This is a difference of 1,915 drivers. In the case of Rural, the database only obtained 78 total drivers registered, which is only 3.24% of the total drivers of Urban cities.

#### Total Fares
In terms of total fares according to city type, Urban cities obtained a total of $39,854.38, adding up to the highest amount of fares by city type. This was followed by Suburban with $19,356.33, and Rural with $4,327.93. 

#### Average Fare per Ride
After gathering the information presented above, we were able to obtain the average fare per ride, in which we observed an interesting fact. While the average fare per ride in Urban city type is $24.53, in Rural city type the average is $34.62. This means that although Rural cities have the lowest number of rides and drivers, it is the category that charges the most per ride. This is probably affecting the low number of trips requested. Lower demand for trips results in higher charges to sustain the service.

#### Average Fare per Driver
We can observe the same situation with the data we obtain from the average fare per driver. In the Urban city type the average is $16.57, while in Rural the average is $55.49. This is a difference of $38.92 dollars, which directly affects the frequency of service requests in rural cities, since the price is high.

### Multiplle-line chart analysis

![PyBer_fare_summary](https://user-images.githubusercontent.com/107893200/182995619-87efc71b-cad7-4bcb-8924-e9de023d835b.png)

In order to perform a more detailed analysis of the total fare by city type we created a graph. For this we selected a period of time to analyze it, and divided it into weeks. This time period was from January 1, 2019 to April 28,2019.

The graph shows that **Urban cities** had the highest total fare, ranging from approximately $1,500 to $2,500. The period of time with the best results were the thir week of February and the first week of March, and the month with the lowest total fare was January. **Suburban cities** follow with total fares ranging from $550 to $1450. The best month for revenue was the third week of February, and the lowest fare months were early January and early April. Finally, **Rural cities** has the lowest total fare amount ranging from $0 to $500. All months have low periods, but the two highest points we can observe in the chart are during the third week of February and the last week of April. 

Comparing the results for each type of city, we can see that for all the month with the best performance was February, where there was an increase in trips during the third week of the month.

## Bussiness recomendations
After reviewing and analyzing of the information we can recommend the following to PyBer:

- In order to have a better result in the number of customers using the platform in Rural cities, it is necessary to study the market. Who uses the service? For which trips they use it? What is the price they are willing to pay? This way they could have a better offer of trips and prices, since not many people use the platform which is causing the prices of the service to be very high. They could even analyze if the service increase in February is due to tourism and not because they use it locally. 
- In the case of Suburban cities, although it is observed that more trips are requested, there are fewer drivers than trips. This coul mean that drivers make more than one trip. PyBer could increase the number of drivers, offering them good pay and safe vehicles, which would increase the availability of drivers to request the service. 
- On the other hand, in the case of Urban cities there are more drivers than rides. The company could analyze whether this is due to the fact that there are very long trips and therefore the number of rides is lower. To improve this Pyber could propose to its drivers to have a certain number of trips per month with a fair fare, in order to complete more trips and have more visibility for the service. Having short trips with a very low fare could encourage drivers to have only long trips to compensate their earnings, which affects the use of the application.
