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
In terms of total fares according to city type, Urban cities obtained a total of $39,854.38 dollars, adding up to the highest amount of fares by city type. This was followed by Suburban with $19,356.33 dollars, and Rural with $4,327.93 dollars. 

#### Average Fare per Ride
After gathering the information presented above, we were able to obtain the average fare per ride, in which we observed an interesting fact. While the average fare per ride in Urban city type is $24.53 dollars, in Rural city type the average is $34.62 dollars. This means that although Rural cities have the lowest number of rides and drivers, it is the category that charges the most per ride. This is probably affecting the low number of trips requested. Lower demand for trips results in higher charges to sustain the service.

#### Average Fare per Driver
We can observe the same situation with the data we obtain from the average fare per driver. In the Urban city type the average is $16.57 dollars, while in Rural the average is $55.49 dollars. This is a difference of $38.92 dollars, which directly affects the frequency of service requests in rural cities, since the price is high.

### Multiplle-line chart analysis

![PyBer_fare_summary](https://user-images.githubusercontent.com/107893200/182995619-87efc71b-cad7-4bcb-8924-e9de023d835b.png)


## Bussiness recomendations
