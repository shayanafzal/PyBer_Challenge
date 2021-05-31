# Overview of the Analysis

The purpose of this analysis is to create a summary DataFrame of ride-sharing data by city type. After that Pandas and Matplotlib will be used to create a multiple-line graph that shows the total weekly fares for each city type. 

At the end a report has been produced that summarizes how the data differs by city type and how those differences can be used by PyBer to make business decisions. Three main recommendations have been summarized at the end.

The coding can be accessed [here](https://github.com/shayanafzal/PyBer_Challenge/blob/553e72b825f27b4caad2fb000546c16742937af1/PyBer_Challenge.ipynb)

# Results 
Please refer to the chart below for a quick summary. Refer below the chart for details.
![GitHub Logo](https://github.com/shayanafzal/PyBer_Challenge/blob/553e72b825f27b4caad2fb000546c16742937af1/Analysis/Chart.png)


## Total Rides
The total rides count increases as one moves from rural to urban, with suburban being in the middle. This makes sense as it appears to be a reflection of the population.

## Total Drivers
The total rides count increases as one moves from rural to urban, with suburban being in the middle. As expected there is a direct relationship between the total number of rides and the total number of drivers. 

## Total Fares
The total fares increase as one moves from rural to urban, with suburban being in the middle.  

## Average Fare per Ride
The average fare per ride is highest for rural and lowest for urban, with suburban being in the middle. This may be because in rural locations places are located further away and require long travel distances. 

## Average Fare per Driver
The average fare per ride is highest for rural and lowest for urban, with suburban being in the middle. 

## Weekly Total Fare by City Type

Please see below graph that summarises weekly total fare by city type. 
![GitHub Logo](https://github.com/shayanafzal/PyBer_Challenge/blob/553e72b825f27b4caad2fb000546c16742937af1/Analysis/Fig1.png)

### Rural 
Over the four month internal the fares in rural areas are fairly consistent.
### Suburban
Starting in January the suburban fares are low and towards the end of April they are high.
### Urban
Starting in January the urban fares are low and towards the end of April they are high.

# Summary

The above analysis leads to the following three recommendations that can best help to improve revenues:

1. The total fare at the start of January is low for Suburban and Urban areas. This needs to be investigated and perhaps new promotions can be introduced to increase the Jan revenue. 
2. Urban areas have almost five times as many drivers when compared to suburban areas. However, this same ratio is not reflected in the total fares. The total fares for urban areas are only twice that of suburban areas. The type of trips people take needs to be analyzed. Perhaps the urban and suburban demographic is very different and they both use the ride services for different reasons. This can be investigated further and could perhaps open up an opportunity to target the other demographic in both urban and suburban areas.
3. The Average rate in urban areas is the lowest. This indicates that the distance traveled in urban areas may be small. Long distance options such as trips to far away airports and weekend get away locations at a far away distance should be explored and can be offered as special rides trips to those living in urban areas in order to boost revenue. 
