# Google Project Capstone - Cyclistic Bike Share
capstone_cycles

Google Data Analytics Capstone: Cycles Nov 23 - Oct 24

## How Do Members and Casual Users Differ?

This analysis delves into the differences between members and casual users of a ride-sharing service, focusing on their usage patterns, ride preferences, seasonal trends, and behaviours. By organising the data into key themes, we can uncover valuable insights that highlight how these user types differ in their engagement with the service.

## Executive Summary: Key Differences Between Members and Casual Users

### Key Insights

#### Usage Patterns

Members account for 63% of total rides, reflecting frequent and routine use, averaging 12.0 minutes per trip.

Casual users, at 37%, prefer longer, leisure-focused rides, averaging 21.1 minutes per trip.

#### Temporal Trends

Weekdays: Members peak at commuting hours (8am, 5pm), while casual users show more flexible usage.

Weekends: Both groups align in usage patterns, likely driven by use of the service as a leisure activity, with casual users matching members’ ride numbers.

#### Seasonal Behaviors

Members maintain consistent duration of trips year-round, however, there is a clear increase to the summer months.

Casual users are highly seasonal, with peak rides and durations in warmer months of the year.

#### Rideable Preferences

Electric and classic bikes are equally popular across both groups, with a slight preference across both user types for the electric bikes.

Casual users dominate electric scooter usage (59%), showing adaptability to new options.

#### Location Trends

Popular routes include West Loop Gate to Merchandise Mart, supported by the Kinzie St Bikeway.

#### Conclusion

Members have a higer degree of consistency and routine, possibly centred around short-distance commutes. Whereas, casual users have more seasonal behaviour, likely based around leisure-based activities.

## Analysis
## Usage Patterns by User Type

### Total Rides

![Ride Numbers by User Type](https://github.com/user-attachments/assets/e7671f6c-ab54-4405-9d51-0346a1ff11d4)

Members account for 63% of the total 5.92 million rides, while casual users make up 37%. This shows that members consistently contribute a larger share of rides. However, casual users still form a substantial portion, making up roughly one-third of all trips.

### Ride Duration

![Average Duration per User Type](https://github.com/user-attachments/assets/c00c8924-52d9-4678-97d7-d152c5aee5e2)

Members' average trip duration is 12.0 minutes, indicating frequent, short rides, likely for commuting.

Casual Users' average trip duration is 21.1 minutes, 76% longer than members, suggesting that casual users take longer, leisure-oriented trips.

### Rides per Minute

![Number of Rides per Minute](https://github.com/user-attachments/assets/4c44a728-d2e4-442b-93b5-3808500b189b)

Members peak at 5 minutes per ride and show a steep decline in rides lasting longer.

Casual users have a similar peak at 6 minutes but maintain a higher proportion of long-duration rides, further supporting their leisure-driven usage.

These patterns reveal that members use the service for routine, short-distance travel, while casual users demonstrate a preference for longer, less frequent trips.

## Temporal Trends

### Weekday Usage

![Weekday - Rides per Hour - Start Time](https://github.com/user-attachments/assets/96a070d3-8c5d-404f-8876-873ad87f75a2)

Members
Peak usage aligns with typical commuting hours: 8am and 5pm. Sharp increases and decreases around these times also suggest commuting is members' primary purpose.

Casual Users
Demonstrate a more gradual usage increase from 4am, peaking at 5pm. Flexible usage pattern indicates mixed purposes, including some commuting but due to the steady increase during the working day, implies that casual users are either using the service for leisure or use the service to facilitate performing their job.

### Weekend Usage

![Weekend - Rides per Hour - Start Time](https://github.com/user-attachments/assets/2715cd82-2893-4ab0-81d4-0de326b98f1e)

Both user types exhibit an inverted U-shaped usage pattern, peaking between 12pm and 4pm.

Casual users continue to increase slightly until 3pm, while members plateau earlier and maintain steady levels until 4pm.

Despite members making up 63% of total rides, casual users roughly match their weekend ride numbers, indicating a significant shift in behavior from weekday usage between members and casual users.

### Insights

Members primarily use the service for weekday commuting, while casual users display more flexibility, with significant engagement during weekends, likely for activities in their free time.

## Seasonal Trends

### Monthly Rides

Peak Month: September

Lowest Month: January

![User Type - Rides per Month](https://github.com/user-attachments/assets/5c3b35f0-8fe8-469b-862c-4a7bf5e82931)

Both user types see sharp increases in rides from January to May/June, leveling off during summer months and peaking in September. Rides decline sharply as the weather becomes colder from September to January.

Members maintain consistently higher monthly ride numbers, at approximately 100k more rides per month than casual users.

### Ride Duration by Month

![User Type Average Duration per Month](https://github.com/user-attachments/assets/88ee9d73-bb03-4cac-a030-062bb2252b9f)

Members show stable trip durations throughout the year, peaking in May (12.96 minutes) and dipping in November and December (10.83 minutes).

Casual users’ trip durations align with seasonal trends, peaking in May (23.67 minutes) and hitting a low in January (14.81 minutes).

### Insights

Members exhibit consistent usage patterns year-round, while casual users are more influenced by seasonal changes, using the service more during warmer months and for longer durations.

## Rideable Type Preferences

### Rides by Type

![Number of Rides per Rideable Type (1)](https://github.com/user-attachments/assets/92e41672-4ea6-4ae1-b029-ca646552a5d6)

Electric Bikes: Account for 3.0 million rides, with usage evenly split between members (63%) and casual users (37%).

Classic Bikes: Total 2.8 million rides, with a slightly higher member share (65%).

Electric Scooters: 144k rides, heavily skewed toward casual users (59%) compared to members (41%).

### Monthly Ride Trends by Type

![Rideable Type - Rides per Month](https://github.com/user-attachments/assets/66fa0f60-02cb-42c5-beef-929a56d7f3bf)

Classic bikes were more popular in winter months (January/February), but electric bikes were the dominant choice for both user types for the majority of the year.

The introduction of electric scooters in late summer caused a sharp rise in rides, particularly in September, with scooters disproportionately reducing classic bike usage.

### Insights

Members and casual users show similar preferences for classic and electric bikes, but casual users were the majority of users of electric scooters for the one month they were available. This suggests casual users are comparatively more flexible and willing to try new options, while members are more inclined to stick to their routine.

## Location Trends

![Member Location Dashboard](https://github.com/user-attachments/assets/12b46cdb-2363-4827-9300-da9037b8c98e)
![Casual Location Dashboard (1)](https://github.com/user-attachments/assets/27378296-e9ea-40b1-99e7-dc21c3e11eaa)


Both user types commonly start and end trips at two key locations: West Loop Gate and Merchandise Mart. These areas are connected by the Kinzie St Bikeway, a central and bike-friendly route. This infrastructure likely drives high ride numbers for both groups.

### Insights

Convenient and accessible infrastructure benefits both user types, but it particularly facilitates members’ consistent commuting patterns.

## Summary

Members and casual users differ significantly in how they engage with the ride-sharing service:

Usage Patterns
Members focus on short, frequent trips, consistent with commuting due to the usage peaks around 8am and 5pm. Whereas casual users also use it for the same purpose as members, the preference appears to be for longer trips, which are likely associated with leisure, indicated by relatively strong weekend usage.

Seasonal Trends
Members maintain consistent year-round usage, whereas casual users’ behavior is weather-dependent, peaking in warmer months. This is shown by the average ride time being relatively consistent for members throughout the year, indicating that even though there are less rides, it is usually being used in the same manner. Whereas, casual users average ride time is similar to the usage throughout the year, with the warmer months gaining more demand. 

Rideable Preferences
Members and casual users have similar preferences for classic and electric bikes, but casual users appear more flexible, with the majority of users of the newly introduced electric scooters being casual users.

Infrastructure Influence
Central routes like the Kinzie St Bikeway drive usage for both groups, but members rely on them more heavily for commuting.

These insights highlight the primary distinctions between members and casual users, with the former representing routine, predictable usage and the latter characterized by flexibility and leisure-driven engagement.
