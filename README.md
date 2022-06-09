# bikesharing

## Overview of Analysis:
Client wants to start a bike share business. Requested an analysis of the data reported by Citi Bike for the month of August in 2019. Jupyter Notebook was used to format the data and Tableau was used to analyze and visualize the data.

## Resources
- Software: Python, Jupyter Notebook, Tableau
- Source Data: 201908-citibike-tripdata.csv from https://ride.citibikenyc.com/system-data

## Results

The tableau public file with the full. An explination of each slide in the story can be found below.
[link to dashboard](https://public.tableau.com/app/profile/justin.n.kirk/viz/Challenge_14_16547128619700/CitibikeChallenge?publish=yes)

<p align="center">
  <img src="https://github.com/justinkirk8/bikesharing/blob/main/Images/August_Peak_Hours.png" width="800" />
</p>

The first slide is a bar graph showing the overall usage by hour of day.

<p align="center">
  <img src="https://github.com/justinkirk8/bikesharing/blob/main/Images/August_Peak_Hours_repair.png" width="800" />
</p>

The second slide highlights that the least used times overall are from 1 AM to 5 AM. This could be a useful down time for repairing / redistributing bikes if employing a night shift is possible. 

<p align="center">
  <img src="https://github.com/justinkirk8/bikesharing/blob/main/Images/Top_Starting_Locations.png" width="800" />
</p>

The third slide showcases that the majority of the bike trips occur downtown in the more densely populated areas. It is important to consider the city you are considering starting a ride share company in to make sure you have an area that is densely populated enough with poor car traffic. 

<p align="center">
  <img src="https://github.com/justinkirk8/bikesharing/blob/main/Images/Checkout_Times_for_Users.png" width="800" />
</p>

The fourth slide shows how long the bike trips lasted. The vast majority of bike trips lasted under and hour. This could potentially indicate that most people are using the bike share to go from one station and traveling directly to another as opposed to checking a bike out for the day. 

<p align="center">
  <img src="https://github.com/justinkirk8/bikesharing/blob/main/Images/Checkout_Times_by_Gender.png" width="800" />
</p>

The fifth slide shows the same graph with the genders broken out. From this we can see that each category of gender follows the same distribution.

<p align="center">
  <img src="https://github.com/justinkirk8/bikesharing/blob/main/Images/Checkout_Times_by_Gender_male_focus.png" width="800" />
</p>

The sixth slide highlights that males seem to use the ride share more often than females.

<p align="center">
  <img src="https://github.com/justinkirk8/bikesharing/blob/main/Images/User_Trips_by_Gender_by_Weekday.png" width="800" />
</p>

The seventh slide indicates that the majority of the users of the ride share are male subscribers. This reinforces the fact that most people using the Citi Bike are intending to use it regularly.

<p align="center">
  <img src="https://github.com/justinkirk8/bikesharing/blob/main/Images/Trips_by_Weekday_per_Hour.png" width="800" />
</p>

 The eight slide indicates breaks out the head map further so we can see the amount of use each day by each hour.

<p align="center">
  <img src="https://github.com/justinkirk8/bikesharing/blob/main/Images/Trips_by_Weekday_per_Hour_work_hour.png" width="800" />
</p>

The nineth slide highlights that a heavy area of use is during the morning and evening rush hours. This mixed with the earlier heat map indicates that the most frequent user is most likely people who intend to use ride share to get to and from work each day. Client should evaluate the city they are considering to ensure there is a central commercial district that is densely populated that will have the same type of userbase. This map presents another potential window for repairs / redistribution of bikes between stations. This window is Monday through Wednesday from 10 AM to 3 PM.

<p align="center">
  <img src="https://github.com/justinkirk8/bikesharing/blob/main/Images/Trips_by_Weekday_per_Hour_weekend.png" width="800" />
</p>

The tenth slide highlights the second highest use time which could be tourists or residence traveling around city at there leisure. 

<p align="center">
  <img src="https://github.com/justinkirk8/bikesharing/blob/main/Images/Trips_by_gender_Weekday_per_hour.png" width="800" />
</p>

The final slide shows the heatmap broken out by gender. This shows confirms what we saw the fifth and sixth slide which is that all genders follow the same distribution and that males seem to use the ride share more often. 

## Summary
The given data suggests that the majority of the bike trips occur during the day on weekends and during rush hours on weekdays. This indicates that the most common uses of the ride share are commuters during the weekdays and tourist / residence during the weekdays. Because of this, it would be advantageous to place bike stations at tourist locations, hotels, apartment complexes, and commercial centers. The group that uses the ride share the most are male subscribers. This coupled with the highest volume being during rush hours indicates that it is very important that any new ride share company has a large commercial / office space district in a densely populated area.  Initially, the data suggested that the best time for repairs would be during the night from 1 AM to 5 AM. However, further examining the data indicates that another window is present between rush hours on workdays. Specifically, Monday to Wednesday between 10 AM and 2 PM. This time frame should be possible since the majority of the bike trips last under an hour. Another option would be to have a set of reserve bikes to allow leeway on repair times. An additional visualization that would be useful would be to examine the starting locations by weekday vs weekend in order to see if certain stations are utilized more by commuters or for leisure purposes. This could provide even larger windows for potential bike maintenance. A second additional visualization would be to create day by hour heatmap that breaks down subscriber vs customer. This could indicate whether most customers are on the weekend vs commuters on the weekdays.
