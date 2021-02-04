# surfs_up

Analyze weather data  using Python Pandas functions and methods, and SQLAlchemy.

## Overview 

The purpose of this project is to retrieve weather data from SQlite database for the months of June and December in Oahu, Hawwaii and get information on temperature trend in order to determine if the surf and ice cream shop business is sustainable year-round.


## Summary Statistics for June and December

To get the summary statistics ,we first extracted June  and December weather data from Climate Analysis SQlite database. We retrieved all the temperatures for the 2 months then converted them into list, created a DataFrame from the list and generated the summary statistics for the month.

### Statistics for June

Statistics showed that  the temperature count in June was 1700. The average temperature in June was 74. The minimum temperature was 64 and the maximum was 85.

![June_temp_stat](https://github.com/assaci/surfs_up/blob/main/June_temp_stat.PNG?raw=true)


## Statistics for December

Statistics showed that  the temperature count in June was 1517. The average temperature in June was 71.04. The minimum temperature was 56 and the maximum was 83.

![Dec_Temp_stat](https://github.com/assaci/surfs_up/blob/main/Dec_Temp_stat.PNG?raw=true)

## Summary
From our analysis , the average temperature for both months June and December were above 70. Even if the minimum temperature for December was 56 the maximum was 83.
As May and February were considered the hottest and coldest months of the year in ohea. We have decided to add more queries for the 2 months. The respective average temperatures in February and May were 69.44 and 73.68. The minimum temperature were 56 and 63 while max temperature were 72 and 87. 

Based these findings we could conclude that surf and ice cream shop business would be sustainable for years in Oehu Hawaii. 

## Statistics for February

![Feb_Temp_stat](https://github.com/assaci/surfs_up/blob/main/Feb_Temp_stat.PNG?raw=true)


## Statistics for May

![May_Temp_stat](https://github.com/assaci/surfs_up/blob/main/May_Temp_stat.PNG?raw=true)









