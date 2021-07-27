# Ford GoBike Analysis

![alt text](https://github.com/Abd97saad/FordGoBike-Analysis/blob/main/ford-gobike.jpg?raw=true)

## Introduction

Ford GoBike is an expanded, re-branded version of the Bay Area Bike Share program, which had just 700 bikes to offer. They're slated to offer 3,500 bicycles at 322 stations by early September and 7,000 bikes at 546 stations in San Francisco, East Bay, and San Jose. by the end of 2018. The bikes are available for use 24 hours/day, 7 days/week, 365 days/year and riders have access to all bikes in the network when they become a member through a monthly or yearly subscription or purchase a single ride or 24-hour pass.



## Dataset

The data consists of information regarding 183,000 bike rides between two locations, it includes information about the rider and the duration of the trip. The data can be found [here](https://www.kaggle.com/chirag02/ford-gobike-2019feb-tripdata).

Here are the fields provided to us in the dataset. It is not necessary to be working with all of these, but it's still good to know what's in here.

```
duration_sec
start_time
end_time
start_station_id
start_station_name
start_station_latitude
start_station_longitude
end_station_id
end_station_name
end_station_latitude
end_station_longitude
bike_id	user_type
member_birth_year
member_gender
bike_share_for_all_trip

```




## Summary of Findings


- **Female takes longer trips than male.** One of the most interesting facts that female has the longer trip average duration than the male. Across all ages, the differences between the duration of male riders and female riders are noticeable. However, the other gender type has a higher average duration than both females and males.

- **Usually people are using the bike for quick rides.** Most of the riders use the bike for a quick trip an average of 6 minutes. This might be because of the subscribers who are going inside the cities between home to school or work. 

- **Ages of _21_ and _40_ tend to ride the bike for a longer time.** Not surprisingly, we have seen the younger people tend to ride the bike for longer trips. People in their 20s and 30s are expected to have longer trips than 40s and 50s. and that's why the right skew does exist in the histogram. 



