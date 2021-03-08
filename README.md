# fordgobike_exploration
Exploring fordgobike Dataset
# Ford GoBike System

>- Bay Wheels is a regional public bicycle sharing system in California's San Francisco Bay Area. It is operated by Motivate in a partnership with the Metropolitan Transportation Commission and the Bay Area Air Quality Management District.
- Bay Wheels is the first regional and large-scale bicycle sharing system deployed in California and on the West Coast of the United States. It was established as Bay Area Bike Share in August 2013.
- As of January 2018, the Bay Wheels system had over 2,600 bicycles in 262 stations across San Francisco, East Bay and San Jose.

## Aly Essam


## Dataset

> - There are 183412 rows in the fordgobike trips dataset.
- The trips in the dataset have 16 variables (duration_sec, start_time, end_time, start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude ,end_station_longitude, bike_id, user_type, member_birth_year, member_gender and bike_share_for_all_trip)
- There are 4646 bikes, 329 start and end stations


> There wasn't much wrangling to be done except:

          >  - The trip duration initial visulization was concentrated around an area That doesn't give enough information or insight so It was changed to minutes instead of seconds and log transformation is used for a better look at the data.
			 - Creating user_age column to be able get an insight on the impact of age.
			 - Creating Day and Hour Columns from the start time to be able get an insight the impact of time.

## Summary of Findings

> After The Univeriate Exploration:

		  > The majority of the trips lasts less than 10 minutes and the trips lasts from 1 to 100 minutes
		  
		  > Most of the users are between 20 and 40 years old.
		  
		  > Most of the users are subscribers.
		  
		  > Most of the users are Males.
		  
		  > Thrusday have the most trips per day and The least trips per day are duting the weekends.
		  
		  > - The most trips per hour are at 8:00 and 17:00 which they are the start and the end of the working day 
			- The least trips per hour are from 0:00 to 5:00 when the users are asleep.

> After The Bivariate Exploration:

		 > - Most of the users are between 20 and 45 years old, the trips for these users takes around 12 mins on average and The users between 60 to 80 years old tend to have longer trips than the other users 

		 > - The customers have higher range of trip duration and higher median duration than the subscribers 

		 > - The Females have the highest median trip duration while the Other genders have the highest range of trip duration 
		   - The Males have the lowest median trip duration and lowest range of trip duration although they are the majority of users

		 > - The weekends ( Saturday and Sunday ) have the highest range of trip and they also have higher median than the working days 

		 > -  The Average trip duration is almost the same except the time between 3:00 as it increased rapidly due to the low trips in these hour
		   - There are a slight increase in the average duration during the working hours between 10:00 and 15:00
		   
		 > - The Other genders have the highest median of users's age and 
		   - The Males have the highest range of users's age
		   - The Females have the lowest median and the lowest range of user's age

		 > - Most of the users during the weekends are between 20 and 30 years old which are younger than the users during the workdays

> Multivariate Exploration:
    
         > - The Females have the highest median trip duration while the Other genders have the highest range of trip duration Through days pf week.
		 
	     > - The Males have the lowest median trip duration and lowest range of trip duration through days of week although they are the majority of users.
		 
	     > - The weekends ( Saturday and Sunday ) have the highest range of trip and they also have higher median than the working days.
		 
		 > - The median of all genders doesn't have significant changes through days of week.
		 
		 > - The Average Trip duration for the customers through the hours of the day is much higher than the subscribers.
    


