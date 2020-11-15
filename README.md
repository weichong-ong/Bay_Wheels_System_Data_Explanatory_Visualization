# Bay Wheels (Ford GoBike) System Data Explanatory Visualization
## Introduction
### Investigation Overview
In this project, I investigated Bay Wheels (Ford GoBike) public datasets. [Bay Wheels](https://en.wikipedia.org/wiki/Bay_Wheels) is a regional public bicycle sharing system in California's San Francisco Bay Area.

The objective of this study is to investigate the bike activity patterns and the effects of trip characteristics on the average trip duration, for Bay Wheels's public bicycle sharing system during a seven-month period. Since April, Bay Wheels changed the structure of their public dataset by including the rideable type (electric or docked bike). Therefore, I used the data starting from April 2020 until October 2020 for consistency purpose. I downloaded the datasets for each months from its [website](https://www.lyft.com/bikes/bay-wheels/system-data) and concatenated them into one single master dataset.
The downloaded datasets can be found in [my GitHub Repo](https://github.com/weichong-ong/Bike_Sharing_System_Data_Explanatory_Visualization) as well.
I went through the steps of an explanatory data visualization, systematically starting from univariate visualizations, moving through bivariate visualizations, and finally multivariate visualizations.
To finishing up, I worked on polishing up selected plots for presentation from the analysis so that their main points can be clearly conveyed to others.

### Dataset Overview
The dataset included information about individual rides made in a bike-sharing system covering three Californa's cities, San Francisco, San Jose and Oakland, for a seven months period, from April 2020 until October 2020. The data consisted of the location of the stations, the time the users picked up and returned the bike, user type and what type of bike they used for the trip. There are approximately 1 million data points. 1057 data points were removed from the analysis due to inconsistencies or missing information.

## Bay Wheels
Bike sharing has emerged as one of the most-trending forms of mobility in the current era. Digitalization has enabled bike sharing to become a fully integrated part of urban mobility.

Bike sharing is popular nowadays because it
- is faster than walking
- is cheaper than taxis and car sharing
- is more flexible than public transport
- requires less maintenance and is less expensive than owning a car
- can be combined with other means of transport

Bay Wheels is the first regional and large-scale bicycle sharing system deployed in California and on the West Coast of the United States.
It is operated by Motivate in a partnership with the Metropolitan Transportation Commission and the Bay Area Air Quality Management District. Bay Wheels is the first regional and large-scale bicycle sharing system deployed in California and on the West Coast of the United States.
It was established as Bay Area Bike Share in August 2013. As of January 2018, the Bay Wheels system had over 2,600 bicycles in 262 stations across San Francisco, East Bay and San Jose. In June 2017 the system was officially re-launched as Ford GoBike in a partnership with Ford Motor Company. After Motivate's acquisition by Lyft, the system was renamed to Bay Wheels in June 2019.

Since April 2020, Bay Wheels offer two types of bikes: docked bike and electric bike. And there are two options for parking the e-bikes:
1. Place ebike in a dock at any Bay Wheels station
2. Use the cable to lock to any bike rack within the service area.

## Explanatory Visualization
Explanatory Visualizations are the key component of the communication at the end of an analysis project. A picture is worth a thousand words.
A good explanatory visualization will help us to convey the findings and impress the audience, be it a friend, boss or the world.

## Summary of Findings
- The average duration of the trip is approximately 12 minutes no matter where the starting point is, when the trip is, what type the user is and what type of the bike the user use.
- On the weekdays, the peak hour users pick up and return the bikes is at around 5pm to 6pm and this is the off-work time for most of the people. On the other hand, the peak hour on the weekends is between 1pm to 3pm.
- The number of trips of member users are consistent every day in the week, whereas casual users have a significant high number of trips on Saturday compared to other days.
- There is no electric bike in Oakland. The number of people used electric bike is three times the number of people used docked bike in San Francisco. And the difference is even larger in San Jose. Electric bike is more popular in California.
- The average trip duration depends on the time the users pick up the bike. Users tend to spend longer time on the trip than average if they pick up the bike in the afternoon, between 1pm to 3pm.
- Generally, users have in average longer trip duration on the weekends.
- Casual users have a longer trip compared to member users in average, and they use electric bikes generally for a shorter distance trip, whereas they prefer docked bike for a longer distance trip.

## Key Insights for Presentation
For the presentation, I dropped out the city variable as it did not give meaningful insights. 80% of the data points are from San Francisco. Therefore, it would not give a fair comparison betweent the cities.
Instead, I focused on independent variables like hour of the day, day of the week, user types and bike types.
The topics that I covered in the presentations are:
1. When are most trips taken in terms of time of day or day of the week?
2. How long does the average trip take?
3. Does the average trip duration depend on
    - if a user is a subscriber (member) or customer (casual)?
    - if the bike used is a electric bike or a docked bike?
    - the time period a user picks up the bike?
