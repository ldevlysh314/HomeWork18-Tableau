	1.	The initial stage of the project involved acquiring monthly CSV files, covering the period from October 2023 to December 2023, from the Citi Bike Data webpage and organizing them in a designated folder named "data". The data used in this analysis specifically pertains to the New York City region.
	2. 	The above css files were combined using Jupiter note book.
	3.	The combined data is saved in file citibike23.csv.  For simplicity, only 3 months were picked from the data stored at City Bike Data webpage. 
Dashboard 1 / Story 1:
Visual analysis of the number of casual rides vs membership based rides.

1st graph: total numbers of casual rides vs membership bases rides.
2nd graph: number of casual rides per week day vs number of membership rides per week day.
3rd graph: count of start rides per hour of the day for casual vs membership rides.
4th graph: count of start rides per day of a week for casual vs membership rides.

The graphs give a clear indication of dominance of membership rides vs casual rides. Regardless of the day of the week, membership usage is more active comparing to casual renting. Same applies to time of a day, specifically we observe increased activity between 6AM with slow down after 7PM.
Considering the research area (New York City), it is safe to connect the displayed activity to work schedules. It appears that for a busy city like New York, with constant traffic issues, CityBike became another option for a work commute. Considering it is less likely for a visitor to sign up for membership, it is safe to assume that it is residents who opt for membership option. The spike of rides between 6AM and 7PM suggests the bikes are used for work commute. That can be confirmed by the fact of higher activity during week days vs weekends. 

This analysis however doesn’t show if CityBike solved the traffic issue in New York City. But proves the demand in another way of commuting. 

NOTE: the dashboard had to be split into 2 due to the difficulty of uploading.

Dashboard 2 / Story 2
Visual analysis of the top 15 most popular start and end stations.

The dashboard consists of 2 charts. 1st shows top 15 most popular station to start rides and the 2nd shows top 15 most popular station to end rides.
By clicking on a station in “Starting” chart, the “Ending” chart will show where the rides from the starting chart ended. 

Unfortunately, the data on longitude - latitude isn’t clear in provided csv’s. Due to limited timing, the cleaning wasn’t performed. With appropriate amount of time available, the graphs would provide information of the cost popular routes for rides. 

However, even with the current representation, it is clear that both charts show pretty much same stations. With might lead to observation, that this is the area of the concentrated usage ion the city bikes. 

Story 3
Map visualisation of bike stations - starting
Map that shows locations of the starting stations with the count of rides initiated per station.

Note: for more accurate presentation, dats needs to be cleaned (discrepancies own the latitude and longitude). Thus it was impossible to map names of the locations. Also, obvious false data for the stations shown in the water.

Story 4
Map visualisation of bike stations - ending
Map that shows locations of the ending stations with the count of rides ended per station.

Note: for more accurate presentation, dats needs to be cleaned (discrepancies own the latitude and longitude). Thus it was impossible to map names of the locations. Also, obvious false data for the stations shown in the water.

Conclusion.
The 4 presented dashboard strongly suggests the popularity of the membership option vs casual of using the city bikes. The bikes are mostly used during weekdays and during work hours. Which leads to believe the bikes are used as another form of public transportation for work commutes by the residents. The overall popularity suggests that the idea of bike renting was welcomed by the community and put to good use. 
If time allowed, it  would be suggested to do a prior data cleaning, particularly the coordinates of the bike stations, to be able to map the names of the stations and also eliminate obvious false data (stations shown in the river).