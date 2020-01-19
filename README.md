# Dashboard And Story Building Using Tableau

## Summary:
Data from Citi Bike Program for the period January to July, 2018, is analyzed by perparing visualizations using Tableau to present reports as dynamic dashboard. Tableau's analytics was leveraged to gain insights from the visualizations.

## Data Source:
[Citi Bike Data](https://www.citibikenyc.com/system-data) :bicyclist:

## Data Preparation:
The total number of records obtained for the 7 months was ~97 million. Since, trip duration is not an important measure for analysis, data was filtered based off of trip duration (< 300), to finally create a dataset of 1.78 million records. All files related to data extraction and aggregation are avilable in "data" folder.

## Visualizations:
The following visualizations have been created:
1. **Monthly Trend For Citibike Riders.** A line plot showing monthly growth trend for the total number of records. Analytics was used to generate a trend line which showed a statistically significant trend with R-square >95% and p-value=0.001.
1. **Forecast Model.** A forecast model for the next 5 months (Aug-Dec) was generated based off of the trend, but it was inaccurate since the sample size did not capture seasonality pattern.
1. **Daily Trend For Citibike Riders.** The trend was further dissected to see higher level of granularity in terms of daily ridership. The plot shows that the number of bikers during weedays is above the average  (i.e. ~250,000) of  total number of bikers as compared to the weekends. Highest numberof bikers is seen on tuesdays. 
1. **Hourly Traffic Trend.** The line plot shows heavy traffic between 7-10am with a sharp peak around 8am on weekdays. In the evening, peak traffic period is between 5-6pm. Weekends see significantly lesser number of bikers, reflected by the plateau shaped plot. Analytics revealed that 95% of the data tend to lie in the shaded area.The plot is interactive and can be filtered to see result for each day.
1. **Bar chart.** The top performing/popular and least popular start stations were identified through a bar chart for the entire period.
1. **Dynamic map of start stations.** A dynamic map that shows how each station's popularity changes over time (by month), zip code data is overlaid on the map.
1. **Gowth of usertype over time.** 2 Pie plots one for the entire period and one showing breakdown through each month were generated to examine user type trends. shows percentage of customer versus subscriber from Jan to Jul. While more than 97% are subcribers for the time period, number of customers have grown over time.
