# Dashboard And Story Building Using Tableau

## Summary:
Data from Citi Bike Program for the period January to July, 2018, is analyzed by perparing visualizations using Tableau to present reports as dynamic dashboard. Tableau's analytics was leveraged to gain insights from the visualizations.

## Data Source:
[Citi Bike Data](https://www.citibikenyc.com/system-data) :bicyclist:

## Data Preparation:
The total number of records obtained for the 7 months was ~97 million. Since, trip duration is not an important measure for analysis, data was filtered based off of trip duration (< 300), to finally create a dataset of 1.78 million records.

## Visualizations:
The following visualizations have been created:
1. **Monthly Trend For Citibike Riders.** A line plot showing monthly growth trend for the total number of records. Analytics was used to generate a trend line which showed a statistically significant trend with R-square >95% and p-value=0.001.
1. **Forecast Model.** A forecast model for the next 5 months (Aug-Dec) was generated based off of the trend, but it was inaccurate since the sample size did not capture seasonality pattern.
1. **Daily Trend For Citibike Riders.** The trend was further dissected to see higher level of granularity in terms of daily ridership. The plot shows that the number of bikers during weedays is above the average  (i.e. ~250,000) of  total number of bikers as compared to the weekends. Highest numberof bikers is seen on tuesdays. 
1. **Hourly Traffic Trend.** The line plot shows heavy traffic between 7-10am with a sharp peak around 8am on weekdays. In the evening, peak traffic period is between 5-6pm. Weekends see significantly lesser number of bikers, reflected by the plateau shaped plot. Analytics revealed that 95% of the data tend to lie in the shaded area.The plot is interactive and can be filtered to see result for each day.
1. **Bar chart.** The top performing/popular and least popular start stations were identified through a bar chart for the entire period.
1. **Dynamic map of start stations.** A dynamic map that shows how each station's popularity changes over time (by month), zip code data is overlaid on the map.
1. **Gowth of user type.** Pie plot showing result for usertype for the entire duration, reveals that there are more subscribers(98%)than customers(2%).
1. **Gowth of user type over time.**  Pie plot with breakdown of user type growth through each month  shows percentage of customer versus subscriber from Jan to Jul.  An interesting trend was observed. It is revealed that there has been a slight increase in the  number of customers from 0.57% to 2.95% and correspondingly a decrease in the number of subscribers from 99.43% to 97%. 
1. **Gender growth of ridership.** A line plot was created and percentage difference was calculated to examine growth of ridership in different gender. The general trend of ridership  reveals a growth of 13.85% in male versus 3.46% in female as opposed to 0.69% .
1.  **Gowth of user type broken down to gender over time.** Plot suggests a growing number of male (1) and female(2) subscribers over the 7 months. The growth of customers has been more or less constant for all genders. 

## Dashboards
The following dashboards have been created with the visualizations. The dashboards are interactive with use of filters to analyze data based on different time intervals, or different genders. The observations and interpretations have been discussed in the findings.
## **Trend Analysis**
![Trend analysis](https://github.com/Harmeet2504/Tableau/blob/master/Dashboard1.png)

## **Popular stations**
![alt text](https://github.com/Harmeet2504/Tableau/blob/master/Dashboard2.png)

## **Growth of user type broken down by gender**
![alt text](https://github.com/Harmeet2504/Tableau/blob/master/Dashboard3.png)

## Findings
1. **Trend analysis (Dashboard 1):** The analyses indicate that ridership is more popular in summer than in winter. The analysis also conforms to expectations that more people commute for work on weekdays and hence peak traffic is seen during official hours i.e. around 8am in the morning and around 5-6pm in the evening.
1. **Popular stations (Dashboard 2):** The top three  popular stations for the entire duration are: W 21 St & 6 Ave, Broadway & E 14 St, Lafayette St & E 8 St. The botttom three or least popular starting stations are:Apache, Prospect Park, 8D QC Station 01. The geo-spatial distribution of the popular stations suggests that they lie in the heart of the city, in commercially active area and hence are more popular. 
1. **Growth of user type broken down by gender (Dashboard 3):** This suggests that while bike riders prefer to subscribe to the service, there is a growing popularity of non-subscribers too. A breakdown of the analysis to examine its popularity by gender(B,right panel) suggests a growing number of male (1) and female(2) subscribers. The growth of customers has been more or less constant for all genders. The general trend of ridership as seen from line plot(B, left panel) reveals a growth of 13.85% in male versus 3.46% in female as opposed to 0.69% of the total percent.

