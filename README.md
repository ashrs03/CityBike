# Bike Sharing Program

## Overview of the statistical analysis

The purpose of this project is analyze the NYC bikesharing data for a busy month, August in a given year and to understand the data using different visualizations. The objective is to make a story based on the analysis through data visualization and to convince investors that a bike-sharing program in Des Moines is a solid business proposal. 

The data was fetched and Pandas import has been used to convert trip duration to a dateTime value and then this data with the new datatype change was used to create visualizations. The baseline analysis that was performed before the dateTime datatype change included looking at the usertype breakdown, gender breakdown, August usage based on count of bikers per hour of the day, top starting locations and ending locations based on the start and end latitude and longitude, average trip duration across the age groups ( mapped with birth year), get a comprehensive visual summary bike id and the number/count of trips and bike utilization details to reinforce understanding on trip duration for each bikeID with a rationale that bikes used more often would have greater need for maintenance and repair. 

Further analysis of data was suggested to look at length of time that bikes are checked out for all riders and genders, number of bike trips for all riders and genders for each hour of each day of the week and abreakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.
The findings and deep dive into the data reflected some patterns and this has been added as a narrative of the story from NYC citybike data. 
Link : https://public.tableau.com/views/Citibike_challenge_16722822507250/CityBikeAnalysis?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link

## Results

### Gender breakdown 
Based on pie chart it is evident that males far outsurpass in using sharerides than woman or unknown category with total count at	1,530,272. The count of female riders in NYC is 588,431 which is almost 1/3rd of that of the males. This could be due to different reasons and showcases that in NYC males are more into city bikesharing program.
<img width="119" alt="Gender breakup" src="https://user-images.githubusercontent.com/42523379/210126701-460a0f29-5cb0-4c0e-944b-8858b19c6b64.PNG">

### Average trip duration 
Younger riders or those born in later years show a distinct pattern of longer trip duration as mapped with birth year. Targetting younder population would make a good strategy for marketing for new bike share program introduction in new city. 

![image](https://user-images.githubusercontent.com/42523379/210127591-382948bd-0a6c-4d14-9958-fad47d7e0a3c.png)

### Checkout times 
From the analysis looking at checkout times for users and checkout times for gender the maximum count of trips is for trip duration between 5 minutes and 59 minutes across all users and as the hours of duration increases the variability increases. This appears logical that for NYC city ride sharing there would be more shorter duration trips. This pattern is seen across genders. 

<img width="679" alt="Checkout time by users" src="https://user-images.githubusercontent.com/42523379/210126704-b6ceaf3d-a304-477c-8297-6c3af85480ab.PNG">

<img width="767" alt="Checkout time by Gender" src="https://user-images.githubusercontent.com/42523379/210126708-c6d5346c-055d-44c5-99f5-760cb73d216b.PNG">

### City bike trips by the hour 
The demand / usage of bikes is most between hours of 7 to 9 am and 5 to 7 pm 
![image](https://user-images.githubusercontent.com/42523379/210127430-040ea973-5bce-4575-bbbd-25cf0ce567c1.png)

### Usage type by Gender by days
Usage is maximum for male subscribers for Thursdays, Fridays, Mondays and Tuesdays in descending order and same pattern is noted for females although usage / demand is much less compared to that for male subscribers. 'Customer' usertypes have less but uniform usage across the gender type.

![image](https://user-images.githubusercontent.com/42523379/210127155-dba5ed2a-5c4a-47fa-9edd-6ba9375fbc70.png)

### Heatmap for trips at each hour across weekdays 
This heatmap shows that more share rides correspond to what would be anticipated as busy hours of morning an devening commute. The most busy time for bikeshar eis Thursdays between 5 and 7 pm and in general it is also busy during other weekday evenings between 5 -7 pm ( except wednesday). The next most busy hours of the day are 8 to 9 am in mornings and also somewhat busy in midday on saturdays and sundays. 

<img width="267" alt="Trips by weekdays for each hour" src="https://user-images.githubusercontent.com/42523379/210126848-53219ee0-8cb5-4ed3-ba5a-0ead907c267e.PNG">

### Trips by gender by the hour of the day
Males have most usage on Thursdays between 7 to 9 am and 5 to 7 pm and the head map reflects less usage for female riders and even less usage for unknown riders. This corresponds to the findings for usage type by gender by days and trips at each hour across weekdays. 

![image](https://user-images.githubusercontent.com/42523379/210127380-10270cb0-a22f-43dd-96f6-e50be94ae0c1.png)

### Top starting and ending locations 
Comparing visualizations for the Top Starting and Ending Locations, we can see that the most active starting locations in busy city area are also among the most active ending locations and it appears like a round trip. This information is relevant for understanding broadly how the needs for bike stock needs to be replinished in a new city where the program is implemented. 
It is important to note that top starting and ending location are mostly clustered around city which would also mean there is more utilization of bike sharing for shorter trips. 
Top starting locations
![image](https://user-images.githubusercontent.com/42523379/210127118-264039ec-b702-4843-a66b-237d4dfcac69.png)

Top ending locations
![image](https://user-images.githubusercontent.com/42523379/210127088-43a783d7-8d82-4eb0-b880-3df72d4220ae.png)

## Summary:
This analysis provides insight into the utilization of bikes in NYC Citibike bike-sharing program. Looking at usertype, gender breakdown, utilization across the time of day for users/ genders, weekend and weekday usage, starting and ending locations, trip duration average time provides important takeaways for planning n bike sharing program for Des Moines. 
One of the next step additional data for DesMoines could be around gender breakdown across customers and subscribers as this can be region specific. Also understanding the trip duration patterns would be useful. In terms of analysis of existing data Weekend usage is more evenly spread with more usage in mid day, so there are few other considerations. Firstly, further analysis for weekday and weekend trip duration and secondly prepare a visualization to determine if there are specific locations that are completely unused.

Tableau story link: 
 https://public.tableau.com/views/Citibike_challenge_16722822507250/CityBikeAnalysis?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link
