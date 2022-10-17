# (2019 Ford Go-Bike Project )
## by (Alagbe Oluwapelumi olaoluwa)


## Dataset
> The data consisted of prices and attributes of approximately 180,500 trips. The attributes included the characterstics such as : duration_sec, start_time, end_time, user_type, start_station_name and end_station_name. Eight thousand three hundred and sixteen data points were removed from the analysis due to inconsistencies or missing information.


## Summary of Findings

> The dataset contains 180,500 observations, and has 16 columns focusing on the bike trip details; the trip duration, start and end times, start and end stations info, and some informations related to the users such as member age, member gender, user type and bike share for all trip  Most of the variables are numerical (9 Variables), 7 object type.

> I made some data tidiness and quality by:
* deleting unnecessary columns
* adding other columns containing duration in minutes, hours and days
* adding two(2) other columns(start_day, end_day) containing day name obtained from start_time and end_time after converting data type to date time
* add member age column 
* creating the time user started their trip and the period of the day(Morning, Afternoon, night)
* change the start_station_id,end_station_id,bike_id datatype to string.

> The findings I got from the investigation of the data are:
* subscriber is greater than customer having 90.5% of the user type and customer having just 9.5%
* the finding establishes the fact that a vast majority of users are Male(128546) rather than Female(40128) and Other with 3595
* majority of the members age are between 18 to 50 years old
* I find the top 10 start stations which Market St at 10th St is rank first where users start their trip.
* most trips commences at the afternoon then follow by morning but fewer at night.
* customers tend to travel for longer durations and Subscribers travel for comparatively less duration. 
* customers has the almost the same frquency but subscribers varies. also, I deduce that subsriber rides more in weekdays compare to weekend.
* subscribers are more than customers in each station. Also, the trips in male riders are way more than in females.
* the age bracket from 20 to 40 has a ranging of trip duration of 5 to 30 minutes and the trip duration narrowing as the age increased
* number of users prefer to ride bike in the morning at 8. Also, people in San Francisco Caltrain Station 2 (Townsend St at 4th St) start most of the rides at 8 am.
* at durations less than or equals to 60 minutes , both customers and subscribers have achieved similar durations of use.
* this plot indicates that women ride for longer periods than men whether customer or subscriber. I also note that there is an even distribution of genders between the 2 user types subscribers and customers.