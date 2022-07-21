# Exploratory-Analysis
# (Bike sharing a feasible scheme or not?)
## by (Chigozie Chukwu)

## Dataset

The Ford GoBike System dataset includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. it has 16 columns including duration_sec; this is the time interval each user rides the bike from one point to another, start_time, end_time, start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude, end_station_longitude, bike_id; this is the identity number of each bike, user_type; shows whether a particular user is a subscriber or customer to the bike sharing scheme, member_birth_year, member_gender, bike_share_for_all_trip; indicates if users rides bike all the all distance being covered. This data set has about 183412 entries.

I loaded my dataset using the .head() method and went ahead to get the general features of my data using the .info() method. There were null values in the dataset, so i droped them. This thus reduced the number of entries in my dataset. I got the general descriptive analysis of the dataset using the .describe() method. 

Yay, my data is good to go for the exploratory analysis. Excited to see what the data says about our title?, lets get to it.

## Summary of Findings

The bikeshare data, as I named the data got us some interesting insights. During the unvariant exploration i found out that, there were more subscribers to the bike sharing scheme than there are customers and the proportion of members that used the bike sharing scheme for all trips were not up to half of those that did not use it. Males used the bike more than the female and other genders. The charts also indicates that there was an initial success in the bike sharing scheme and the younger generations utilized the bike sharing scheme more than the older adults. The members did covered smaller distance with the bike and rarely used it for all trips. 

Going on the bivariant exploration, I found out that the total members were more of males and most of them were subcribers to the scheme. Although, most of them did not use the bike in the sharing scheme for all their trips, they all covered a smilar distances with the bike. Those of younger age group spent more time(in seconds) riding the bike than those of older generation.

Finally, the multivariant visualization shows that, the total of male and female that rode on the bike used for the scheme for a greater duration of time were almost similar. I also noticed that the total number of subscibers and customers that rode the bike that were born in 2001, only used the bike for a shorter duration of time. Moreover, just one member(a female) born in the 1880's rode the bike for some seconds during the bike sharing scheme. The customers and subcribers who fall under other gender used the bike for a longer duration(above 1500 secs), which contrast that of the male and female.

## Key Insights for Presentation

1. The younger generations should be a priority in building bikes for the scheme;

The proportion of male and female that used the bike for a longer duration were equal, while only a few others rode the bike for that same duration. Interestingly, this chart shows that only one female born in the 1880's used the bike, despite the duration of its use being about 1000secs. This shows that more people born in this new generation were the the majority of the members of the scheme.

2. The bike sharing scheme was a feasible one.

There was an initial success in the bike sharing scheme as more members were involved when more bikes were introduced.
