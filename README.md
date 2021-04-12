# PyBer_Analysis

## Overview
V. Isualize wanted to look into the performance of each city type.  By computing some basic summary statistics, we were able to easily compare the total rides, drivers, and fares, as well as the average fare per ride and average fare per driver for all three types.  She then asked to look into the weekly fare of each type for the first four months of 2019 and, ultimately, plot the findings in a multiple line graph.  This all was performed in the hopes that it would lead to more informed business decisions that address the disparities between the city types.

## Results
When we look at the summary of the PyBer data, we can see the city type has a significant influence on every metric we measured.
(PyBer Summary)![image](https://user-images.githubusercontent.com/79211628/114201880-4aeb4a00-991c-11eb-9bfb-9e63eedc9aad.png)
Total rides, drivers, and fares all increase as we go from rural areas to more urban ones.  From Rural to Suburban areas, the total fares increase by 347% and from Rural to Urban areas, the same metric increases by 821%!  Even when moving from Suburban types to Urban, all three metrics at least doubled.  When averaging these statistics, we observe the opposite effect.  The average fare per driver and average fare per ride both decrease as we move from Rural to Urban.  This is due to the total fares, although they still increase moving from Rural to Urban areas, increase at a slower rate when compared to the total rides and drivers' increases.

Moving on to the weekly performance by city type, our visualization confirms our expectations of Urban cities outperforming their counterparts.

(Total Fare by City Type)![image](https://user-images.githubusercontent.com/79211628/114205708-33ae5b80-9920-11eb-9fef-d72d4372ce29.png)

As we can see in the chart,  Urban cities earn the most, then Suburban, and, finally, Rural cities on a weekly basis.  Urban cities earned up to six times the amount Rural cities did in certain weeks!

## Summary
There are a couple ideas that come to mind when deciding how to attack the disparities between city type.

- I would suggest taking some of the Urban drivers and sending them out to the Suburbs.  This will obviously decrease driver supply in Urban cities, possibly lowering Urban city revenue, but at ~$16 a driver in Urban areas and ~$40 a driver in Suburban ones, we can expect to more than offset those losses overall.
- Based on our chart, it looks like revenues in Urban cities are lower in the first couple weeks of the year.  This seems like a perfect opportunity to send drivers out to the Suburban and Rural areas due to the lower opportunity cost of driving out there compared to in the Urban cities.
- Finally, we can see from our summary table that the only city type that has more drivers than rides is the Urban type.  This leads me to believe the Suburban and Rural drivers are underutilized resources due to the lack of demand for rides. I believe targeted ads in the Suburban and Rural areas could increase awareness, and therefore demand, of PyBer in those areas, turning the wages we pay our underworked Suburban and Rural drivers into a more efficient use of capital.
