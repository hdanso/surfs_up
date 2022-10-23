# Investing in Hawaii Waves and Ice Cream

## Analysis Overview
The purpose of this analysis was to determine the suitability of Oahu, Hawaii as the prime location for an exciting new business venture - a Surf and Shake shop serving surfboards and ice cream to customers. Using SQLAlchemy to query SQLite databases, temperature data was extracted to get statistical insights to the weather trends in stations throughout Oahu.

## Results
An analysis of the data reveals 3 key difference in weather trends between June and December:

1. The average Oahu temperature in June is 3.9 degrees hotter than the average Oahu temperature in December; 74.9 degrees in June vs. 71.0 degrees in December.
2. The maximum Oahu temperature in June is 2 degrees hotter than the maximum Oahu temperature in December; 85 degrees in June vs. 83 degrees in December
3. The minimum Oahu temperature in June is 8 degrees hotter than the minimum Oahu temperature in December; 64 degrees in June vs.56 degrees in December.

The figures below summarizes the statistical findings for weather data in June and December:

<img width="150" alt="June Temp Stats" src="https://user-images.githubusercontent.com/96188669/197411861-570f4204-0176-4ffe-9918-a3f53064d941.png">
<img width="173" alt="Dec Temp Stats" src="https://user-images.githubusercontent.com/96188669/197411869-48f5a152-8776-4f05-9100-282974125a49.png">


## Summary
In summary, the results indicate that June is generally a warmer month than December in Oahu. Although the difference in min, average, and max temperature between the 2 months is not extremely large, it may be worth noting as even the slightest temperature dip can influence ice cream + surfboard buying habits.

Additional queries that can be built to further analyze weather data for June and December include querying the database to get information on precipitation data as this can greatly influence the success or failure of the Surf and Shake, as well as finding the number of observations from each station for June and December. Finding the number of observations for each station can provide an insight to how reliable the data is - more observations = more reliable, vs. less observations being less reliable
