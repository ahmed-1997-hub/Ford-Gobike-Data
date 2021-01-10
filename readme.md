# (Ford GoBike System Data)
## by (Ahmed Khaled Mohamed)


## Dataset

> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.

> This data Collected in 2019 with 183,412 raws data trips for fordgobike in the dataset with 16 Coulmns (duration_sec, start_time, end_time, start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude ,end_station_longitude, bike_id, user_type, member_birth_year, member_gender, bike_share_for_all_trip), with a missing values in (start_station_id, start_station_name, end_station_id, end_station_name, member_birth_year, member_gender).


## Summary of Findings

> Accordint to the gender, duration,and age analysis
- By increasing the age after 40 the number of the rider dereases and the trip duration deareases also.
- Riders from 30 to 40 takes a shorter duration in their trips.
- The duration of the trips in female riders decreases from age 35.
- But the female riders data is much less than male riders "data unbalanced".

> Acoording to user type and days of week analysis
- The short period of usage for subscribers with concentration on rush hours Monday through Friday, indicating the use is primarily for work commute. 
- The subscriber take shorter time and much quicker than customers, and the duration for trips increases in saturday and sunday for the two types.
- The long ride for customer that they're taking advantage of the bike sharing system quite differently from the subscribers, and concentration of customer trips in weekends and in the afternoon.

## Key Insights for Presentation

> Most of the data concentrated between hour 06 and hour 22, with peaked around 8-9am and 17-18pm during a day.
> The main members in the dataframe is males with 74.6% and females with 23.3%.
> The main members in the dataframe have a False in bike_share_for_all_trip by 90.1%.
> The main members in the dataframe was a Subscriber in user_type by 90.5%.
> Most of the members age concentrate in 30s & cncentated between 20 to 70.
> The trips distance frequent but concentated in 0.5 to 2.5 KM with high number of members from 0.5 to 1.2 KM
> The sation with Id 58 is the most frequent station members start their trips from it maybe this station have the member with age 30s
> the station with Id 67 is the most frequent station members end their trips from it.