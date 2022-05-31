# bikesharing

## Overview
Citibike, a bikesharing company people use to rent bikes directly from bike stations placed all around a city, has a huge presence in New York City. Citibike data from the month of August 2019 was analyzed to understand better how it works in NYC, and then determine if it could be a successful business in Des Moine, Iowa. 

## Results

[link to dashboard](https://public.tableau.com/app/profile/claire3124/viz/M14NYCCitibikeChallenge/M14Story?publish=yes)

All of these results are using data from Citibike in New York City during the complete month of August 2019. 

### High Level NYC Citibike Users Breakdown

Going by the Citibike data of August 2019 in New York City, there are over 2 million rides per month, the user is most likely to be male, and subscribers use bikes more than customers (who pay per trip versus pay a subscription). 

![High Level Overview of Users](/Image_Resources/Overview_Stats.png)

### Bike Trip Duration and Start and Stop Times

Most bike trips are under 20 minutes long, no matter if the rider is male or female. It is rare for bike trips to last 40 minutes or longer. Also, the most popular times for trips during the weekday (Monday - Friday) are during regular commuting hours (7-9am and 5-7 pm). During the weekends, people ride Citibikes throughout the daytime (approximately 9 am to 7 pm).

![Bike Trip Duration and Ride Times](/Image_Resources/Checkout_Times.png)

Also, these trends hold no matter the gender of the rider. That is, commuting hours are more popular on weekdays and daytime hours are more popular on weekends throughout the whole day, despite whether the rider is male or female.

![Bike Trip Duration and Ride Times](/Image_Resources/Usage_Time_by_Gender.png)

### Popular Starting and Ending Locations

Many of the most popular bike stations for starting trips are also the most popular stations for ending bike trips. Also, the most popular bike stations overlap with the highest population density areas of New York e.g. Manhattan and Brooklyn. Also, there are a high number of stations surrounding the most popular stations, so bikers don't have to ride super far to find another station to return their bike.

![Bike Trip Duration and Ride Times](/Image_Resources/Start_and_End.png)


### Conclusion Visual

This image shows, based on the intensity of the colors, that male subscribers are the highest represented customers using Citibike. This data also shows that weekdays are more popular than weekends, in general, for subscribers, while weekends (Saturday and Sunday) are slightly more popular than weekdays for customers. This likely means that tourists and New Yorkers who want to use Citibike to navigate the city for fun are using the bikes as customers on the weekends, while people who live in the city and use Citibike for commuting to work are more likely to be subscribers to the biking service. 

![Bike Trip Duration and Ride Times](/Image_Resources/Total_Data_Summary.png)


## Summary

The data on Citibike riders in New York City showed that riders are more likely to be male, to be subscribers, and to start and stop trips at popular stations in the densest parts of the city. The data also showed that subscribers are more likely to use the service during the weekdays for commuting, while customers are more likely to use bikes on the weekends, presumably for sightseeing and having fun. Finally, there were over 2 million rides in the month of August 2019. 

I would propose building the following visuals to further analyze the possibility of launching Citibike in Des Moines.

1. A line graph of number of rides per month over the course of 1 or 2 calandar years in NYC. How much is ridership impacted by the seasons? Given Iowa has similar seasonal patterns as New York, can usership patterns for Des Moines be extrapolated from this?

2. Create a pie chart of the number of trips that start and stop in the same location versus the number that start and stop from a different location. If a sizable percentage start and stop at different locations, I'd try building a series of heat maps filtered by time of day to see the most popular starting vs ending locations. This could be important for understanding where the distribution of bikes need to be set up to maximize the number of rides each day. 