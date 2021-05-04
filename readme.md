# (Ford GoBike System Data)
## by (Kareim Hassanin)


## Dataset

> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. The Bikeshare.com website and platform is owned and managed by Cyclehop, a private bike share company.
> The data set describe 183412 trips in the dataset with 15 features (duration_sec, start_time, end_time, start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude, end_station_longitude, bike_id, user_type, member_birth_year, member_gender, bike_share_for_all_trip). Most variables are numeric in nature, but needed to be in the correct data type.
> The following questions checked during the data work:
> 1- How long does the average trip take?
> 2- Does the above depend on if a user is a subscriber or customer?
> 3- If the age of the subscriber have effect on the trip duration?
> 4- If the age of the subscriber have effect on the usage frequency?


## Summary of Findings

> 1- Most of the trips duration are extetnded to 2000-3000 sec (33 - 50 min) with 500 sec (8.3 min) as the most common duration time.
> 2- Most of the trips user ages are extetnded to from 20-60 year, with 35 year as the most common age.
> 3- Most of the trips user are males.
> 4- Stations 58, 67, 81, 21, 3, 15, 30, 5, 22, 16 are the highest 10 start stations used.
> 5- Stations 67, 58, 21, 15, 3, 30, 81, 6, 5, 16 are the highest 10 end stations used.
> 6- The most common user type who use the app is subscribers.
> 7- There are negative relation between the trip duration and the age of users, meaning the younger users complete the trips in shorter time.
> 8- The trip duration tend to be a little longer for females than males (males tend to be faster).
> 9- The age of the user have no effect on the user type.
> 10- Males tend to to use the customer account type much more the females.
> 11- Males with older age tend to use the app than the females.
> 12- Males with yonger age tend to make the trips in time shorter than the females of the same age.
> 13- Subcribers males take longer trip durations than females, while the female customers take longer trip durations than males 
> 14- There is no diffrence between the user types of both males and females in the trip start time

## Key Insights for Presentation

> 1- Investigation of user type: Need more cleaning and poilshing, by removing the others from the genders, and adjusting the plot.
> 2- Investigation of correlations between the user gender and user type: Need more cleaning and poilshing, by removing the others from the genders, and adjusting the plot.
> 3- Investigation of member genders: Need more cleaning and poilshing, by removing the others from the genders, and adjusting the plot.
> 4- Investigation of start and End stations: as the number of the highest 25% most used stations are very high, concentration the insight on just the highest 10 only.


## Resources

> Course materials
> https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.dropna.html
> https://www.youtube.com/watch?v=-6HmdijtWwk
> http://damianavila.github.io/blog/posts/hide-the-input-cells-from-your-ipython-slides.html
> https://stackoverflow.com/questions/886716/controlling-bars-width-in-matplotlib-with-per-month-data
> https://stackoverflow.com/questions/18098061/change-the-ticklabel-orientation-and-legend-position-of-plot
> https://stackoverflow.com/questions/36573789/python-seaborn-facetgrid-change-xlabels
> https://stackoverflow.com/questions/29813694/how-to-add-a-title-to-seaborn-facet-plot
> https://stackoverflow.com/questions/25129144/pandas-return-hour-from-datetime-column-directly

