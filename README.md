# PyBer Analysis

## Analysis Overview
The purpose of this project was to analyze PyBer ride sharing data and summarize the data by city type: Urban, Suburban and Rural. Once a summmary dataframe was created, the next step of the analysis was to filter the data by city type and date to understand the fare total for each city type based on a certain time frame in 2019. This pivoted data was then plotted in a multi-line chart to visualize the differences in fare total between city types. The goal of these materials is to help PyBer stakeholders understand the major differences in ride share data by city type and use that information to make business decisions.

## Results

### Ride Sharing Data Summary
Below you'll find the summary dataframe of the ride sharing data organized by city type.

![PyBer_Summary_2](Analysis/PyBer_Summary_2.png)

The data shows the total rides, total drivers, and total fares by city type along with the average fare per ride and the average fare per driver. Based on this analysis, the conclusion is that:
- Rides in Urban cities acount for 68.4% of all rides, compared to only 5.3% for Rural cities.
- There is a negative correlation in the data between number of rides and drivers and average fare per ride. Higher fares are associated with lower number of total rides and lower number of drivers.
- Urban cities are the only city type where there are more drivers than total rides. 
- Rural cities have the fewest drivers compared to number of rides, suggesting that there is more demand in rural locations which correlates with higher fares.
- Urban cities have the highest number of rides and the highest total fare amount, but the fare per ride and the fare per driver is lower compared to suburban and rural cities.
- The average fare per driver is 235% more for rural drivers and 138% more for suburban drivers than for urban drivers.

### Total Fares by City Type Over Time
Below you'll find the summary graph of the ride sharing data organized by city type for weeks between Jan - April 2019.

![PyBer_fare_summary](Analysis/PyBer_fare_summary.png)

Here, you'll see the fluctations in total fares by city type per week. This analysis shows that:
- Urban cities consitently have higher fare totals than suburban and rural cities week over week.
- Suburban cities also have higher fare totals per week than rural cities.
- All city types saw the lowest fare totals in January compared to other months.
- All city types saw a spike in fare totals the 3rd week of February.
- Rural and urban cities saw an additional spike in fare totals in the last week of March, while suburban fare totals decreased. 
- At the end of April, suburban fare totals increased while urban and rural fare totals decreased.

## Summary
Based on these conclusions, here are 3 recommendations for the PyBer team to address disparities among the city types.
1. Given that urban cities have more drivers than rides overall, it's recommended that some drivers consider taking rides in suburban and rural cities vs. only urban areas to capitalize on the demand in those locations
2. This should also address concerns over average fare totals per driver. If the % of drivers per ride is evened out across city types, there will be less disparity in average fare total per driver. 
3. Looking at the fare totals over time, the PyBer team can make strategic decisions around how many drivers are needed for certain times of year. Early January is a slow period for all city types, so fewer drivers should be needed then. However, PyBer should make sure that the most drivers are available during the third week of February, when there was a spike in fare totals across all city types.

Overall, while there is consitently more fare totals coming from urban cities throughout the year, it's important that PyBer determines the right number of drivers needed to meet that demand. At this time, there are too many drivers in urban cities compared to the fare totals these cities are generating, causing a large disparity in average fare per driver in urban cities compared to suburban and rural cities.
