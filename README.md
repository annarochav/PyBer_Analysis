# 🚀 PyBer_Analysis
Challenge Week5 Data Analysis BootCamp using Python/ Jupyter Lab / Pandas / Numpy / Matplotlib
## ⚡Overview of the analysis:
Assist PyBer, a ridesharing company with an analysis of the total weekly fares for each city type which are: urban, suburban, and rural. Datasets were made using Python and Pandas and to get the plots, Matplotlib. We’ll see in this analysis metrics such as total rides, total drivers, total fares, average fare per ride and driver etc., this information will help PyBer to understand the consumer behavior and economic trends.

## ⚡Results: 
**PyBer Ride-Sharing Data**

We can see in this bubble chart that circle size correlates with driver count per city and that the average fare tends to decrease as the total number of rides per city increases, especially with the urban type. The suburban type has a higher average fare than the urban and the rural type has the least number of drivers and rides, but the average fare range is the highest. 

<img src="https://github.com/annarochav/PyBer_Analysis/blob/main/analysis/Fig1.png" width="600" height="" />

**Ride Counts by City Type**

We can see that this box-and-whisker plot shows that the urban ride count data it’s the only one with an outlier of 39 rides and the median rides are 24. The suburban type has 17 as median rides and the lowest is the rural type with 6. In the pie chart we can see that the 68.4% of the total rides were made in urban cities. 

<img src="https://github.com/annarochav/PyBer_Analysis/blob/main/analysis/Fig2.png" width="550" height="" /><img src="https://github.com/annarochav/PyBer_Analysis/blob/main/analysis/Fig6.png" width="460" height="" />

**Driver Counts by City Type**

This box-and-whisker plot show the driver count data per city type. The urban type has a median of 37 drivers, the suburban a median of 16 and the rural 4. In the pie chart its clear that the urban area has the biggest percentage with a 80.9% and the rural area represents 2.6%.

<img src="https://github.com/annarochav/PyBer_Analysis/blob/main/analysis/Fig4.png" width="550" height="" /><img src="https://github.com/annarochav/PyBer_Analysis/blob/main/analysis/Fig7.png" width="460" height="" />

**Fare Counts by City Type**

This box-and-whisker plot show the ride fare data by city type. We can see that the median fare for rural cities is higher than the rest, it’s $37 USD. The suburban type is in second place with a median of $31 USD and the urban type $24.50 USD. In the pie chart that urban cities have the highest percentage with 62.7% of rides, whereas suburban cities have 30.5% total fares and rural cities have 6.8%.

<img src="https://github.com/annarochav/PyBer_Analysis/blob/main/analysis/Fig3.png" width="550" height="" /><img src="https://github.com/annarochav/PyBer_Analysis/blob/main/analysis/Fig5.png" width="460" height="" />

**Total Fare By City Type (Resampled, By Week)**

The line graph shows the total weekly fares per city type. Urban areas have the highest revenue in comparison to suburban and rural. The 3 city types have a pick in the last week of February, the rural area seems more stable than the other 2. For a deeper analysis it would be great to have more data to see what might have caused the ups and downs.

<img src="https://github.com/annarochav/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png" width="950" height="" />

## ⚡Summary:

Based on the above results, we can conclude the following:

<img src="https://github.com/annarochav/PyBer_Analysis/blob/main/analysis/Fig8.png" width="600" height="" />

Ridesharing pricing models work with the supply and demand basis, if the demand for rides exceeds the supply of drivers, the fare price increases, like in the rural area were they only have 2.6% of drivers and the total fare is higher than the other types of cities, the average fare per drivers is $55.49 USD, they earn more money than the rest. PyBer may consider investing in advertising to get more drivers into the team.

Urban cities have the highest percent of drivers 80.9% so the fare per driver tend to decrease $16.57. PyBer may consider investing in advertising at the beginning of the year and in the last week of April so the can reduce staff turnover. Overall, the urban area has the highest earnings ($39,854.38 USD).
The suburban area it’s in the middle of the performance, their trends seem stable and doing great, so PyBer can focus their investments in the Urban and Rural city types.



