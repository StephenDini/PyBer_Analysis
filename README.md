# PyBer_Analysis
## Original Directive
creating visualizations of rideshare data for PyBer to help improve access to ride-sharing services and determine affordability for underserved neighborhoods.
## New Directive
create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, create a multiple-line graph that shows the total weekly fares for each city type. Summarize how the data differs by city type and how those differences can be used by decision-makers at PyBer.

# Results:
![ride-share-difference]("analysis/ride-share-difference.png")

Taking a look at the table above, There are a few things to take note of. 

## Rural Areas
These areas have very little rides and drivers but the drivers get paid more. This would make since because of the distance the drivers will have to drive. 

## Suburban Areas
Similar pattern here, While it has more riders and drivers than Rural it is still quite a bit less than Urban areas where everything is within close proximity. The driver get paid more to compensate for the distance between points. 

## Urban Areas
Interestingly there are far more drivers than rides being requested. This affects the average fare each driver gets. Urban areas are the only areas where the "Average Fare per Ride" is higher than the "Average Fare per Driver"

There are so many people working an urban area that it affects the pay for all driver. 

# Summary:
In summery I would recommend three key adjustement. 

1) Even though the distance traveled is far more in an rural area the earning potential is far greater. It would be best to incentivize more drivers to work rural areas. 

2) Urban areas is congested with drivers leading to more workers sitting idle and making less. This group would be the best area to source drivers from to send to rural areas. 

![Total Fare by City Type]("analysis/PyBer_fare_summary.png")

3) There are two spikes in fare prices that all match with all areas except for Suburban areas in april. My recommendation is to reach out and extend any form of communication to see why Suburban areas follow the pattern in febuary but not April. 