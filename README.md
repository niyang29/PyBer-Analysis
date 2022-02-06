# PyBer-Analysis

## Overview of the analysis:

V. Isualize requested Omar, my supervisor, and I to create visualizations to improve access to ride-share services and determine affordability for underserved neighborhoods. After having created and presented several visualizations, V. Isualization had a final request to create a multiple-line graph to illustrate the total weekly fares for reach city type - Rural, Suburban, and Urban cities. This analysis will further help PyBer and V. Isualize better make decisions. 

## Resources: 

We analyzed and merged two data sets city_data.csv and ride_data.csv using Jupyter Notebook, imported pandas, and matplotlib libraries. 

## Results:

There are major differences in rides, total drivers, average fare per ride and averager fare per drivers. Please see table below - 

![PyBer Summary](https://user-images.githubusercontent.com/96089187/152670348-b0b2e4e4-f85d-40d0-bc99-5328dfda6da1.png)

* There are 13 times more rides in urban cities, 1,625 rides, compared to rural cities, with only 125 rides. 
* There are 2.6 times more rides in urban cities, 1,625 rides, compared to suburban cities, with 625 rides. 
* The total fares in urban cities, $39,854.38, are 2 times higher than suburban cities, $19.356.33, and 9 times higher than in rural cities, $4,327.93. 
* The average fare per ride is the most expensive in rural cities, at $34.62, in comparison to the average fare per ride in urban cities, at $24.53. The average fare in urban cities is approximately $10 less than that in rural cities. 
* The average fare per driver in urban cities, $16.57, is about 3 times less than that of rural drivers, $55.49, and 2 times less than that of suburban drivers, $39.50. 

![PyBer Line Analysis](https://user-images.githubusercontent.com/96089187/152670597-34e339c4-41ea-45a0-b643-e306d6211f0c.png)
(also see PyBer_fare_summary.png in analysis folder)

This multi-line visualization illustrates that urban cities (yellow line) is higher than suburban cities (red line) and rural cities (blue line) indicating that ride-share companies have more total fares and revenue in urban cities than other types of cities, and rural cities have the lowest total fares and revenue. 

## Summary:

In summary, I'd like to offer 3 points for V. Isualize and PyBer to further consider -
* While the total fares in urban cities had the highest revenue at $39,854.38, and rural cities total revenues were only at $4,327.93, urban cities are not as profitable as rural cities.
* In order to increase profit margins in urban cities, it is in V.Isualize and PyBer's best interest to reduce the number of drivers in order to increase average fare per ride and drivers. 
* Some further analysis that PyBer should consider is looking at the length (time) of rides and/or the distance of rides per city type to learn if it's time or distance that is costing the total fares to be so high but the average fare per ride to be so low.  
