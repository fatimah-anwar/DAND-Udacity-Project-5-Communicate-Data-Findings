# Project 5 | Ford GoBike System Data Exploration
## by Fatimah Almohammedsaleh


## Dataset

2018 Ford GoBike System dataset contains information about individual rides made in their bike-sharing system covering the greater San Francisco Bay area in 2018.
The dataset consists of 1851950 bike trips in which each record has the following features (after cleaning):

- Trip Duration (seconds)
- Start Time and Date
- End Time and Date
- Start Station ID
- Start Station Name
- End Station ID
- End Station Name
- Bike ID
- User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)
- Bike Share for All Trip (this is a boolean column which indiacte if the trip is part of Bike Share for All option which is affordable, accessible transportation option)
There is only one numerical column left in the dataset after cleaning which is trip duration, one categorical (nominal) column which is User Type, and one boolean column which is Bike Share for All Trip. As for starting and ending time and date, both are of the date data type, while the rest of the columns are strings.

## Summary of Findings

Trips duration distribution:
- Trips duration are normally distributed with one peak at 8 to 10 minutes, Also, and the majority of trips had duration of 30 minutes or less.

Trips starting date and time distribution:
- In general, the time period from May to October witnessed the highest number of trips.
- October is the highest month with total number of trips of about 200,000 trips, followed by July then June. 
- Weekdays have a percentage of 82.4% of the total given that Tuesdays have the highest number of trips, which is about 300,000 trips in total. 
- 57.33% of the trips were taken in the evenings and the highest number of bike trips had usually started at 5:00 PM followed by 8:00 AM. The hours with the least number of trips are between (12:00 AM to 5:00 AM).

User type distribution:
- Approximatly, 85% of the total number of trips were taken by subscribers and that exceeds the percentage of customer trips by almost 70%.  

Bike Share for All Trips distribution:
- 8.72% of the total number of trpis were by users who were part of "Bike Share for All" trip option.

Relationship between trips duartion and the rest of variables:

- Bike trips that start after 8 AM are more likly to have longer duration.
- June and July respectivly have the two highest average trip durations, while Novermver had the lowest avererage duration.  
- Weekndes seems to have the highest average trip durations compared to weekdays, and there are slight diference amonge avergae duration in the weekdays among themselfs
- Trips taken bay customers have higher average durations than the ones taken by the subscribers.
- The avergaes of the Share for all trips members and non-memebrs are close to each other. 

Relationship between user type and trip start time (Month , Weekday , Time of the day/Hour):

- The distibutions of the number of trips for both users type amonge the months are closley similar, exepct that the number of total sucbsribers has jumped to its highset count while the total of customers trips continued to decrease.
- The number of trips made by the subscribers has higher counts in the weekdays (Tuesday has the highest count) compared to the weekends, while the customers takes more bike trips in the weeknds.  
- Customers tend to take relativly high number of bike rides in the time period form 8:00 AM to 5:00 PM in comparision to the rest of the day with 5:00 having the highst number of trips. As of the subscripers, the highest number of trips apperes only at 8:00 AM and 5:00 PM, and much lesser numbers in the period in between. 

Relationship between "Bike Share for All Option" and trip start time (Month , Weekday , Time of the day/Hour):
- Members of "bike share for all" tend to heve higher number of trips than non-members in Jun and July.
- Members of "bike share for all trips" have the highest number of taked trips at 5:00 PM while non-member have the highest number in the time periods  8:00 AM and 5:00 PM.
 __________________________________
 
 - It seems that Customrs are more likely to take longer trips duration in allmost all the times of the day.
- None members of "bike share for all" trip option seems to take longer trip duration than those who are members.
- Trips made in the evenings tend to be longer on avergae than the ones made in the mornings in almost all days of the week exept for Sundays.
- Trips made by Customers tend to be longer on avergae than the ones made by subscribers in almost all days of the week.

## Key Insights for Presentation

For the presentation, I start by introducing the invistigated variables
and their distribution along with the plots 

Afterwards, I introduce the relationships amonge these variables.