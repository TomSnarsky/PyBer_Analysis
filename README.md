# PyBer_Analysis

## Overview of the Analysis

This new analysis summarizes the data with a particular view towards summary statistics and trends differentiated by city type. While our prior analysis also tracked the different city types (Rural, Suburban, and Urban), this analysis deepens our earlier work by considering unit metrics (fare per ride, fare per driver) and by carefully examining time-series data disaggregated by type of city using a multiline graph. The former advancement will allow us to control for the significant disparities in the total numbers of rides and drivers in the three different city types, and the latter focus on analyzing over time will allow us to look at trends sensitive to seasonal changes (for example) or other temporal dimensions our prior analysis couldn't consider.

## Results

Below are results from the two new deliverables which are products of our new analysis: a summary DataFrame by type of city and a multiline graph of fares from selected dates in 2019.

### Summary DataFrame

<img width="595" alt="image" src="https://user-images.githubusercontent.com/99628051/160319282-95ebc1cc-5977-4021-9fb4-16ce4d0c41b3.png">

This summary DataFrame gives us the total rides, total drivers, total fares, average fare per ride, and average fare per driver for each of the three city types: rural, suburban, and urban. Two things become immediately apparent when the data is summarized in this way: first (and in accordance with our prior analysis), urban cities represent the highest volume of rides, fares, and drivers -- followed by suburban cities, then by rural cities with far and away the smallest total numbers. Second, however, the summary data presents an important insight belied by the first: the fact that, per ride and per driver, rural cities actually have the highest average fares, followed by suburban and then urban cities, respectively.

This second insight may not be quite as surprising as it first seems: rural cities may be more widely laid out, leading to longer trips, and the increased relative demand for drivers (since they are fewer in total number, as we also know from the summary DataFrame) may push people to accept higher/surge pricing or other determinants for higher fares. Conversely, the shorter trips and higher driver counts in urban areas help to make sense of their lower average fares.

### Multiline Graph

![image](https://user-images.githubusercontent.com/99628051/160320716-bcf121b8-2b6d-4d32-8b64-3be132e80d18.png)

This multiline graph examines fare data across a stretch of several months in early 2019 and disaggregates it by type of city (rural, suburban, and urban once again). Although a bit less definitive in the conclusions we may draw from it than the summary DataFrame was, there are a few insights worth gleaning from this data representation: first, there is a discernible spike in fares in all three types of cities right around the end of February, which might merit further investigation; did this coincide with any piece of PR or maybe a promotion that is worth repeating? Was there perhaps a multi-city event or some sort of holiday that increased customer usage and should be marketed more actively during this period in future years? That question aside, there are also a few important differences that this data helps to make clear: for example, as the time series nears its end in April (spring has sprung, weather is getting warmer, etc.), only one of the three types of cities has fares trending *up* -- suburban cities, whose fares are rising comparatively aggressively as urban and rural cities exhibit a gentle diminution. This raises an important question of how to leverage this fact which we will pursue in the next section. Lastly, it is worth noting that urban cities experience multiple peaks during the months of March and April, some of which are echoed in the suburban/rural data, but not all. These peaks are equally worth investigating.

## Summary

Below follow our three recommendations pursuant to our new analysis.

### First recommendation: Rural driver recruitment program

Our first recommendation is perhaps our most ambitious: starting a recruitment program to increase the number of drivers in rural cities. The statistics in our summary DataFrame could serve as powerful recruitment tools to encourage prospective drivers to sign up and join the app (especially since they would be making more per ride and per capita than their urban and suburban counterparts!). Of course, this kind of recruitment program would best be matched with further marketing efforts in rural cities to concomitantly increase demand, but a) we acknowledge that our marketing department is working with finite resources that may best be spent elsewhere (like on our third recommendation!) and b) we do not wish to ignore the fact that rural cities still represent the smallest total fares and ride counts overall.

### Second recommendation: PR/Marketing/calendar review

The time series data in our multiline graph suggest that it could be beneficial to look into past PR efforts/promotions, along with perhaps gathering data from users, to see if the peaks in fares correspond to any particular events or marketing efforts. If we were able to identify a particular holiday or ad campaign that proved to increase fares, we could be more strategic and proactive in capitalizing on either again in the future.

### Third recommendation: Urban incentives

Last but not least, both new data summaries/visualizations support a glaringly true fact we knew from our first analysis: urban drivers and users form the backbone of our business, with by far the largest share of rides, fares, and drivers. To that end, we believe it would be worthwhile to explore particular incentives that would especially serve these users, to promote customer loyalty in an ever-growing field of ridesharing app competition. Moreover, further analysis could be conducted into specific urban cities to see if there are context-specific opportunities for promotion and incentive (for example, could there be a reward system for folks with multi-state urban commutes like we see in NYC, or perhaps something to support commuters burdened by high tolls like in the DC metro area?).
