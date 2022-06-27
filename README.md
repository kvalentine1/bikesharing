# NYC Citibike Analysis

Overview

The purpose of this analysis is to see if the Citibike program of bike sharing in NYC could be used as a basis for a similar program in Des Moines, Iowa. To determine if this would be a good investment for the city of Des Moines, the data for August 2019 NYC Citibike rides was cleaned and then analyzed and visualized in Tableau. This data covers multiple points such as ride durations, bike station locations, type and genders of users, among others.

Link to Tableau Story:

Results of the NYC Citibike Analysis

1.	Number of Rides 
The total number of Citibike rides in August 2019 was 2,344,224 rides. Info regarding population and visitation of NYC and the Citibike program was also obtained. 
2.	Rides per bike ID
About 1/3 of the bikes had the most rides per bike with the most used bike having 479 rides that month.


3.	Trip Duration
Using a line chart, we see that the majority of ride durations are under 1 hour. The peak trip duration is 5 minutes.
4.	Trip Duration by Gender
This line chart shows that peak ride duration times is consistent between males and females with male rides peaking at 5 minutes and female rides peaking at 6 minutes. This visual also illustrates that the overwhelming users of the bikes are males.
5.	Trip Duration by Usertype
Next, we broke down the ride durations into intervals of 5 minutes as well as user types. The average ride duration is consistent with the previous visualizations. This visualization highlights that most users are subscribers of the program.  This also highlights that most subscriber rides are 10 minutes or less whereas customer rides dispersed fairly evenly between 5 and 25 minutes.


6.	Trips by Weekday per Hour
Next the data was analyzed in terms of time of ride and day of ride. The trend shows that bike usage is more concentrated on weekday mornings and even while on the weekends, the rides are distributed more evenly throughout the daytime.
7.	Trips by Gender (Weekday per Hour)
When the data is broken down between genders, peak ride times are proportional between males and females. 
8.	Start Times and Stop Times
This next visualization breaks down ride start and stop times by user type. When both customers and subscribers are selected, the peak usage time trend is consistent with the visualizations of trips by weekend hour. Of note, most of the rides are occurring during traditional work hours and business operating hours.

When we apply the filter as subscriber rides only, we can see that while subscriber rides are primarily between 7 am and 9 pm, there are two peak time periods. There is a high concentration of subscriber rides between 8 am and 10 am and between 4 pm and 8 pm. This trend coincides with traditional morning and evening rush hour times.

When the customer filter is applied, the trend shifts and the number of rides by customers increases from 8 am to later afternoon/early evening before decreasing in the later evening and night hours.


9.	August Peak Hours
Using a bar graph and a stacked bar graph, we see consistency among trip start times from the preceding visualizations. Bikes are most heavily used between 6 am and midnight. This would suggest that it would be best to perform repairs and preventative maintenance on the bikes from 2 to 5 am.


10.	Ride Start and End Locations
These maps show that the majority of rides started and ended within Manhattan south of Central Park. There were high concentrations of rides starting and ending from Midtown south to Battery Park and along the Hudson River. While there are a fairly significant amount of rides in Brooklyn and a few in The Bronx, ridership in the outer boroughs is practically nonexistent. 
11.	Ride Start and End Locations by Usertype
When the usertype filter is applied to the station locations maps, the trend remains consistent that most rides start and end below Central Park. Since there are more subscribers than customers, most stations have more subscriber rides. However, higher concentrations of customer rides are again seen along the Hudson River. Also of significance, there are more customer rides bordering Central Park and on Governors Island than there are subscriber rides. This suggests that the customers may largely be tourists. 




Summary

There are a few key takeaways from this analysis. First is that the vast majority of bike users are subscribers. Additionally, males use the bikes significantly more than other genders. Secondly, ride durations are usually short, less than an hour, and mainly occur during daytime and evening hours. Gender does not appear to influence ride times but user type does show influence over what time of day the rides are being taken. Lastly, the bike rides are heavily concentrated within Manhattan, specifically south of Central Park. Based on these factors, I believe it would be fair to assume that the majority of rides are taken by male subscribers within Manhattan during rush hours.

While offering an alternative form of transportation during commute times is a benefit to present to the city of Des Moines, additional data and analysis is needed to determine if this is a viable program for Des Moines to implement. Additional data that could assist with the analysis would be user zip codes and age range. Age would be crucial to determining what generations are taking the most advantage of the bike sharing program. Zip codes would be incredibly helpful so that we know what area the users are from. This can help determine what NYC riders were tourists versus locals. This could also be used in conjunction with Census data to provide more demographic background of the users. Tableau provides the ability to present data on maps using Census filters such as median age, per capita income, blue collar versus white collar areas. Below I have included a visualization showing ride start and end locations using the per capita and population map layers illustrating how the layers could aid in the analysis of the data.
Additional visualizations for this analysis would also be helpful. The data as presented has the station coordinates longitude and latitude separated. Combining the data into a full coordinate would aid in visualizing active routes. By creating a map showing which start and end station combinations get the most use, we can use the map layers to see what landmarks (such as schools, attractions, and business areas) users are using the bikes to access. Another visualization could be what times certain stations are most active. And additional visualization could use filtering to see how often a specific user ID is frequenting the same start and end stations. Knowing the frequency a subscriber uses a specific route compared to a customer can give more insight into how heavily the Citibike program is being used as a form of commute transportation or leisure transportation. Finally, the data should be visualized in a way to show the locations a bike ID is accessed. A third of the bikes had heavy use. If bikes are being used between a few busy stations and getting hundreds of rides monthly, it may be worth keeping track of those trends so that less used bikes at less used stations could be swapped with heavy use bikes to distribute wear and tear across all bikes more evenly.

In summation, while the data provided visualizes significant points about the bike sharing program, it is not enough to determine if this would be a viable program in Des Moines. The differences between NYC and Des Moines are significant regarding population, annual visitors, city size, and city layout. The way a bike sharing program works for NYC would probably not be viable to Des Moines as is. But with additional data, a proposal could be made that fits Des Moines’ needs whether that be accessible transportation to underserved communities, to students on and off college campuses, creating traffic jam relief, or any other needs Des Moines may have.
![image](https://user-images.githubusercontent.com/101373173/176032707-0b63e233-d46d-4269-bfaf-ba46a7ce6760.png)
