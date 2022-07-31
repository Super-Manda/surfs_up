# :swimming_man: Surf's Up!  :surfing_woman:

## :icecream: Overview of the analysis: 
### Purpose:
- This will analyze temperature and precipitation information to determine whether the conditions in Oahu are favorable to opening an ice cream and shake shop that can be frequented year-round.  Trends in precipitation will be discussed as part of an additional set of queries.  An overall graph for time period 2010 to 2017 will be presented.

## :ice_cream: Results: 
### Three key differences in weather between June and December 


- 1.  The mean temperature in June was 75 degrees, while the mean temperature in December is 71 degrees, which is comparable. 
- 2.  The minimum temperature in December is only 56 degrees versus 64 degrees in June.  The maximum temperature in December is 83 degrees while the maximum temperature in June is 85 degrees.  Generally, this means that, regardless of whether it is June or December, when the temperatures are near the minimum, people will not likely be at the beach, and when the temperature is at the maximum, people will be at the beach.  The June versus December temperature comparisons alone do not suggest any impediments for a prospective business owner who wishes to open a shake shop all year round in Oahu, Hawaii.   
- 3.   There were 1517 temperature readings in December and 1700 in June, which may have impacted the differences in standard deviations (3.75 in December and 3.26 in June).

## :shaved_ice: Summary: 

### Two Additional Queries to gather more weather data for June and December:
-	1.  The first query is for the June precipitation.  June seems invariably dry based upon the standard deviation and the precipitation mean of 0.14.  

![June_Precipitation]( https://github.com/Super-Manda/surfs_up/blob/main/Images_%26_Extras/June_Precipitation.png)

-	2.  The second query is for the December precipitation.  December seems to be a wetter month at 0.22.  

![December_Precipitation](https://github.com/Super-Manda/surfs_up/blob/main/Images_%26_Extras/December_Precipitation.png) 

-	Overall, based upon the max numbers of both June and December, it suggests that when it rains hard enough to reach the max, this is likely caused by a hurricane.  


### Main findings 
- Looking at June and December alone seems to ignore the other ten months of the year.  Thus, I graphed all readings for the entire dataset.  

![All_Time](https://github.com/Super-Manda/surfs_up/blob/main/Images_%26_Extras/Temp_Precipitation_All_Time.png)

- Regarding temperature, June to October seems to be a cyclical finding for the warmest months.  

- Regarding precipitation, all of the outlier points can actually be traced to specific weather events, most of which occurred from June to December; however, looking at the general trends in precipitation, the time period from November to March seems to precipitate more in terms of regular rain.  That is not to say that the regular rain would necessarily last all day during beach hours or is substantial enough to turn away tourists and beachgoers.  For example, if it rains most often at midnight, that has no impact on this business.  One would have to analyze further to determine if the business would be able to operate at least 260 workdays per year to compare with working a typical 9-5 job, as this business owner essentially may have to cease working during hurricanes, times of all-day precipitation, and chilly days instead of having set weekends or set days off.  

**Nevertheless, based upon this dataset, nothing so far would outright hinder this businessperson because the typical rainfall is small regardless, and the average temperature has a line of best fit that appears horizontal (suggesting overall stability).**
