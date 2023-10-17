# (Ford GoBike System Data Analysis)
## by Abdulafeez Adefabi


## Dataset

> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. There are 183412 fordgobike trips in the dataset with 16 fields (duration_sec, start_time, end_time, start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude ,end_station_longitude, bike_id, user_type, member_birth_year, member_gender, bike_share_for_all_trip).


## Summary of Findings

> The duration of most trips are less than 2000 seconds. The most common duration is 600 seconds. Amongst the days of the week, Thursday is the busiest, recording the highest bike trips. As per the hour mark, the 8th hour and 17th hour had the highest count of trips. 
Regarding stations, San Francisco Caltrain Station 2 and Market St at 10th happened to be the busiest. 91% of the users of ford bike share were subscribers. Approximately 75% of the users were males.

> I found that there was no definite linear relationship between the age (derived from the birth_year column) and duration variable. Longer trips occured on weekends than on weekdays. The male gender whom accounted for 75% of the riders had a lower duration average, covering lesser distance than other gender classification. The customer user_type also covered more distances than the subscribers.


## Key Insights for Presentation

> I analyzed the duration by user_type, gender and day of the week. I had to extract some new columns from existing columns. Derived columns included start_month, end_month, start_day, end_day, age, start_hour and period of the day.
 I started by checking out trip frequencies by user_type, gender using seaborn countplot.I used the boxplot plots of duration across genders and user type. A point plot was then used to visualize the relationship between user_type, days of the week and duration of trip. Similarly, I showed a plot for gender, days of the week and duration of trip relationship.
