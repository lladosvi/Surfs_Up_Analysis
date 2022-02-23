# Project Overview

We are analyzing temperature trends in Oahu to determine the viability of a surf and ice cream shop on a year-round basis. To do this we are looking particualrly at temperature data for the months of June and December in Oahu, this will help us determine if the business is sustainable year-round. The source data for this analysis comes from file: hawaii.sqlite. Then we used Python, Pandas functions and methods, SQLAlchemy, and SQLlite to conduct the analysis. 

# Results

Below we are presenting the summary statistics calculated for June and December and then hihglihting the mayor differences found.

## June Temperature Statistics

![image](https://user-images.githubusercontent.com/96096924/155424763-7e256501-26d0-4a13-b42d-f4f1c9d6235d.png)

## December Temperature Statistics

![image](https://user-images.githubusercontent.com/96096924/155424859-c326a2bf-eed6-4492-b6aa-b0be145bc517.png)

## Observations

- The average recorded temperature in June is about 75 degrees F, 4 degrees higher than the average temp in December. This represents a -5% change in average temperature from June to December.
- The standard deviation in December is larger than the one in June , showing more variation in temperatures. 
- The min and max diferential is also larger in December than June also showing a wider distribution of temperatures. 

# Summary

Even though temperatures recorded in December seem to vary more than those of June, both months would still provide appropriate weather conditions for both surfing and ice cream consumptions. The average temperatures in June and December only differ by 4 degrees and even with some lower lows in December there seems to be enough pbservations at reasonable temperatures to conduct the business. 

I would recommend additional analysis to provide more insights into the size of the business. In addition to temperatures , rain could also influence both surfing and ice cream consumptions so I would recommend to conduct 2 similar queries for rain in June and December, then look at data similarly to what we have done above. 
