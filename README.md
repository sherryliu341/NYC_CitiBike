# NYC Citibike Analysis
MODULE 14 - Citibike analysis

## OVERVIEW
### Purpose:  The purpose of the current analysis is to prepare visualizations that give potential investors a look into the highly-successful NYC Citibike bike-sharing program, so that they can see for themselves that a bike-sharing program in Des Moines is a solid business proposal.  Among others, we have prepared visualizations that 1) Show the length of time that bikes are checked out for all riders and genders, 2) Show the number of bike trips for all riders and genders for each hour of each day of the week, and 3) Show the number of bike trips for each type of user and gender for each day of the week.


## RESOURCES
  - Source Files: 201908-citibike-tripdata.csv, 201908-citibike-revised_tripdata.csv
  - Software:  Tableau, Python 3.7.6, Jupyter NB, Pandas Library


## RESULTS
#### The results of our analysis have been incorporated into a [story on Tableau Public](https://public.tableau.com/profile/john.ramonetti#!/vizhome/NYC_CitiBike_Visualizations/FinalPresentation?publish=yes)

  - [POINT #1](Images/Pt1.png) - Comparing visualizations for the **'Top Starting Locations'** and **'Top Ending Locations'**, we can see that the most active starting locations are also among the most active ending locations.  This is important, because we need to know whether there might be an excess or shortage of bikes at particularly stations over time.

  - [POINT #2](Images/Pt2.png) - Looking at visualizations for **'Checkout Times for Users'** and **'Checkout Times by Gender'**, we see that most rides are for 20 minutes or less, and that the vast majority of rides are less than one hour.  We also see that this pattern is the same regardless of gender.

  - [POINT #3](Images/Pt3.png) - The **'Gender Breakdown'** pie chart shows that males in NYC utilize the bikesharing program almost 3 times as often as females.  Further analysis is needed to understand why this is the case.

  - [POINT #4](Images/Pt4b.png) - The heatmap of **'Trips by Weekday per Hour'** shows a clear pattern of bicycle useage 1) during the morning weekday commute (7-9 a.m.), 2) during the evening weekday commute (4-7 p.m.) except on Wednesday evenings, and 3) all day long on weekends.

  - [POINT #5](Images/Pt5.png) - The **'Trips by Gender (Weekday per Hour)'** heatmap shows that the useage pattern is true regardless of gender, although the total numbers for males is considerably higher.

  - [POINT #6](Images/Pt6.png) - The **'User Trips by Gender by Weekday'** heatmap demonstrates the following points:  subscribers are mostly male and account for most of the weekday activity,  customers' gender are often unknown,  and useage on the weekend is more evenly split between subscribers and customers.

  - [POINT #7](Images/Pt7.png) - Our **'Bike Utilization'** and **'Bike Repairs'** charts show that some bikes are used for many trips and many total hours, while other bikes are hardly used at all.  More analysis is called for to assess whether there are predictable patterns of use for high- or low-use bikes. 



## SUMMARY
### The results of this analysis have given insight into the utilization of bicycles in the NYC Citibike bike-sharing program. We've seen the patterns of useage by time and by gender.  Utilization rates can now be predicted based on time of day and location.  Weekday useage is heavily concentrated around the morning and afternoon commute.  Weekend useage is more evenly spread through the day.  We would recommend further analysis for a few points.  Firstly, while we've seen that the vast majority of trips are 30 min or less, we should perform further analysis to compare weekend trip durations to weekday trip durations.  We should also look further into the patterns of useage for the bicycles that see the heaviest use, perhaps preparing maps showing all of the starting/ending routes/locations for the heaviest use bikes.  We should also prepare a visualization to determine if there are specific locations that are completely unused.
