# Bikesharing

## Overview
In a dense city environment, it is often the case that inhabitants can easily travel to their destinations by either walking or taking public transportation.  However, there may be cases where walking to a destination would take a significant amount of time, yet the destination is not quite far enough to justify waiting for a train or bus.  For this reason, bike sharing has recently become a popular method of traveling in a city environment.  Most major cities have some form of bike sharing program that allows users to rent a bike for the desired amount of time, which determines what a user is charged for use.  For this project, a dataset collected from the Citi Bike program in New York City was used to create insightful visualizations related to bike sharing.  In doing so, these visualizaions were used to determine if a similar program could be instituted in Des Moines, Iowa.

## Results
![MAP1](https://github.com/Mots94/Bikesharing/blob/main/Images/Tableau_Map_1.PNG)
**Viz 1: Starting Points**

Based on this visual, it appears that most bike riders start their trips in the Southern half of Manhattan.  The most common starting location is located at Grand Central Terminal.  The next most common starting location is at Union Square Park.  The third most common starting point is near multiple schools, parks, and the Hudson River.

![MAP2](https://github.com/Mots94/Bikesharing/blob/main/Images/Tableau_Map_2.PNG)
**Viz 2: Ending Points**

Similarly, the most common ending points appear to also be in the Southern half of Manhattan.  It just so happens that the three most common end points are the same as the three most common starting points in the first visual.  Major train stations, parks, and schools appear to be the most popular starting and ending locations.

---

![TRIP_TIME](https://github.com/Mots94/Bikesharing/blob/main/Images/Tableau_Trips_1.PNG)
**Viz 3: Trip Time**

This visual displays total trip time in minutes on the x-axis and the number of bikes used for that particular trip time on the y-axis.  The most common trip time was five minutes, and for trips greater than six minutes the number of bikes rented begins to decrease.  At the 14 minute duration point, the number of bikes rented is half that at the five minute duration point.  Based on this graph, it appears that a majority of users rent bikes to travel to a destination within about 3-12 minutes from their current location.

![TRIP_TIME2](https://github.com/Mots94/Bikesharing/blob/main/Images/Tableau_Trips_2.PNG)
**Viz 4: Trip Time by Gender**

In addition, this visualization was broken down by gender of users.  It appears that both male and female users follow a similar pattern.  Between about 1-6 minutes the number of bikes rented increases, and drops off after the 6 minute mark.  The decrease in bikes used by females is more gradual than for males, and it also appears that there were more bikes rented out by males than females.  Other visualization created may help to explain this disparity.

---

![HMAP1](https://github.com/Mots94/Bikesharing/blob/main/Images/Tableau_HeatMap_CustomerType.PNG)
**Viz 5: Customer Type Heat Map**

Shown above is a heatmap, with darker color indicating a higher number of trips taken.  Across the board, bike sharing subscribers take many more trips than customers that are not subscribers.  Taken together with the previous visual, the subscriber base for this service may simply be majority males, which would explain the large number of trips taken by males.  Despite this finding, subscribers take more trips than non-subscribers throughout the week between both males and females.

![HMAP2](https://github.com/Mots94/Bikesharing/blob/main/Images/Tableau_HeatMap_StartHour.PNG)
**Viz 6: Starting Hours Heat Map**

This heatmap displays the number of trips taken using the same coloring method as the previous visual.  This map is broken down by day of the week as well as the start time hour.  It appears that the highest activity times throughout the week are between 6 AM and 9 AM, as well as between 4 PM and 8 PM.  This makes sense, as these are the most common commuting times throughout the work week.  Additionally, on Saturdays and Sundays bike rentals are consistenly higher throughout the day, starting at about 9 AM and ending at 8 PM.  Since most individuals do not work on the weekeds, it would stand to reason that bike trips are consistently high all day because indiviuals have more free time to do what they want.

![HMAP3](https://github.com/Mots94/Bikesharing/blob/main/Images/Tableau_HeatMap_StartHour_Gender.PNG)
**Viz 7: Starting Hours Heat Map (Gender)**

Finally, this heatmap displays the same information as the previous, but also breaks down the number of trips by gender.  As was seen in visual number four, there are similar patterns between males and females as far as the hours that most bikes are checked out.  Throughout the week, men and women more commonly rent bikes during the commuting hours mentioned above.  Over the weekend, men and women both rent more bikes between the hours of 9 AM to 8 PM compared to other hours of the day.  The only real difference is that there are more bike rentals overall by males than females.

## Summary
The first two visuals showed popular starting and ending points throughout Manhattan.  Lower Manhattan had some of the busiest rental stations for both starting and ending points. This seems to indicate that users are traveling to destinations relatively close to their starting positions, that would otherwise be too far to walk.  For users, this may be more convenient than taking public transporation because there are no wait times.  The pricing for this bike share program is $3.99 per 30 minute trip, or $15 a month for unlimited 45 minute rides.  Comparatively, MTA advertises a fair of $2.75 per trip for most subway and bus rides.  If, for example, an individual were to use public transit to commute to work, they may end up spending more than $100 a month on fairs.  If it is viable to commute via bike, the $15 a month subscription seems like a more cost effective method of commuting.

As seen in visuals three and four, the most popular trip duration time based on number of bikes rented is five minutes total.  This confirms that most users are traveling to destinations relatively close to their starting position.  For trip durations between three and ten minutes, there were over 100,000 bikes rented 
