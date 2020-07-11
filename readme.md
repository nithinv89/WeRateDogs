# Flights Data Visualization
## by Nithin Venugopal


## Dataset

> In this Project, we will be using Flights dataset taken from [Stats_Computing](http://stat-computing.org/dataexpo/2009/the-data.html). The Flights dataset essentially shows information of Flights from the US and includes data from 1987 to 2008. This rich data source contains so many variables for analysis including details pertaining to delays, flight information, causes of delays, taxi in/out, date etc.
For my project, I am only including the analysis of the year 2007 since my system had touble encorporating all the data which surpasses to 1.5 GB.
> My data contains 2389217 rows and 29 rows. The data contains daily aircraft data from many carriers from 2007. Most data types as integers and strings. Any data that contains time is represented in minutes.
> As a Data Analyst and an avid traveller, my interest lies in finding out which are the worst airlines with respect to the delay of departure and arrival and how these values are correlated. I want to also explore the other reasons for delays per month and also finally look into the various delays with respect to the 5 Worst Airlines with respect to the delay time.
> The feature that would help me analyze this dataset includes
- Month
- Unique Carriers
- Departed Delay Time
- Arrival Delay time
- Various Delay causes such as weather, carrier delay etc

## Summary of Findings

### What is the relationship between Arrival, Departure and Elapsed Delay
We can see that the Departure Delay follows extreme right skewness while Arrival Delay is slightly right skewed. The Elapsed Delay tends more towards the normal distribution. What conclusions can we make?
- If we witnessed both Departure and Arrival Delay to be the same distribution, we could have concluded that all flights that have a departure delay should also have an Arrival Delay. This is not the case and hence we can conclude that although Departure Delays can cause Arrival Delays, this is not certain for all scenarios. 
- Since all plots have the same y-axis, I feel transformation will only be an extra step to come up with the same conclusion
- This does not need to be in the explanatory analysis since we dont have definitive findings on the same.

### Worst airlines in Terms of delay
- We can see the worst performers of 2007 in terms of delays. There could be so many reasons for this poor performance which we will explore as we go further
- This can be shown in the explanatory analysis since it is a definitive result and can can a story on the data

### Relation between Arrival Time Delay, Departure Time Delay and Elapsed Time Delay
> - Left: we can see that there is a strong correlation between Departure Delay and Arrival Delay. But in general the Departure Delay seems to be slightly more than Arrival Delay
> - Right: It seems that the arrival delay has some correlation with Elapsed time Delay but overall the correlation is not strong enough since the scales are different
> - Centre: There is no correlation between Departure Delay and Elapsed Time Delay
- Since this is definitive and does continue the story from the univariate exploration, it should be a part of the explanatory analysis.

### Delays compounded by Month
> Here we can see the best month to travel where the mean delays are much less than the rest of the year. Further analysis needs to be done on all the years to see if this pattern is consistent throughout. We will also need to see city by city calculation to know more about this pattern
- This can be shown in the explanatory analysis since we are finding patterns from the plot

### Line Plot comparing the various causes of delays with respect to month
> Here we can see that the 2 main reasons for Delays are the Weather and also the Late Arrival of the plane. It is also interesting to note the variation of these delays does differ month to month drastically.
- This can be shown in the explanatory analysis since the pattern of delays throughout the year is seen to differ

### Line Plot comparing the various causes of delays with respect to the worst performing carriers
> In the 2nd plot, we can see that the aircrafts that showed high departure and arrival delays essentially had the blame on themselves where the carrier delay and Late aircraft delay seemed to be the highest factor.
- This should be in the Explanatory analysis since we are showing where the delay for the carriers come from.

## Key Insights for Presentation

### Line Plot comparing the various causes of delays with respect to month
> Here we can see that the 2 main reasons for Delays are the Weather and also the Late Arrival of the plane. It is also interesting to note the variation of these delays does differ month to month drastically.
- This can be shown in the explanatory analysis since the pattern of delays throughout the year is seen to differ

### Line Plot comparing the various causes of delays with respect to the worst performing carriers
> In the 2nd plot, we can see that the aircrafts that showed high departure and arrival delays essentially had the blame on themselves where the carrier delay and Late aircraft delay seemed to be the highest factor.
- This should be in the Explanatory analysis since we are showing where the delay for the carriers come from.