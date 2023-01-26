
# NYC CITI BIKE SHARING PROGRAM

## Project Overview

The NYC Citi Bike Sharing program implemented in Tableau is a data visualization project that aims to analyze and present the usage patterns of the Citi Bike sharing system in New York City. The project will utilize Tableau software to create interactive dashboards and visualizations and represent as story in the end that will allow users to explore the data in a variety of ways. The data will be sourced from the Citi Bike System Data Page for the Month of August 2019, which provides information on trip duration, gender, birth year , start and end times and stations. The project will focus on identifying patterns and trends in the data, such as peak usage times, popular bike stations, and trip duration. The goal of the project is to provide insights that can be used to improve the Citi Bike system and make it more efficient and convenient for users.

## Resources
Data Source: Citi Bike Data - 201908-citibike-tripdata.csv.zip
Software : Python, Jupyter Notebook, Anaconda, Tableau Public

## Results
  The Datasource used for this project is from CitiBike System Data Page for the month of August 2019. 

 The File has 2.3 million records with the information about the following categories
 - Trip Duration 
 - Start Time and Date
 - Stop Time and Date
 - Start Station Name
 - End Station Name
 - Station ID
 - Station Lat/Long
 - Bike ID
 - User Type (Customer = 24-hour pass or 3-day pass user; Subscriber = Annual Member)
 - Gender (Zero=unknown; 1=male; 2=female)
 - Year of Birth

  The Trip duration provided was a numeric whole number and we have to change it to represent in DateTime format which has been implemented using Pandas and exported the new processed file to be used for Tableau.

## NYC CitiBike Basic Data
  The Tableau report shows that there are 2,344,244 total rides and 13,983 bikes in use during the month of August 2019. This averages to 6 trips/ day.

<img src="https://github.com/hsurisetti/BikeSharing/blob/main/screenshots/BasicData.png" width=400 />
## Checkout Times for users
  Trip Duration per ride : Most of the rides have a duration of 30 minutes or less

<img src="https://github.com/hsurisetti/BikeSharing/blob/main/screenshots/CheckoutTimesForUsers.png" width=400 />

## Checkout times by Gender
  The report shows that the serive has been predominatly used by men than women with an approxsimate ratio of 3:1

<img src="https://github.com/hsurisetti/BikeSharing/blob/main/screenshots/CheckoutTimesByGender.png" width=400 />

## Trips by weekday per hour
   A Heatmap has been generated to show the status with the peak timings from 7 AM - 9 AM and 4 PM - 7 PM during the weekdays. The weekends seems to be a little bit more evenly distributed.

<img src="https://github.com/hsurisetti/BikeSharing/blob/main/screenshots/TripsByWeekdayperHour.png" width=400 />

## Trips by weekday by gender per hour
 The report shows that men use the service more than women . Both men and women ride bikes around the same time of the day.

<img src="https://github.com/hsurisetti/BikeSharing/blob/main/screenshots/TripsByGender.png" width=400 />

## User Trips by gender  and weekday
  The subscribers are the main users of the system with Make being the highest followed by female. The demographic data also shows some unknown population . But in general the ratio between male and female shows 3:1 

<img src="https://github.com/hsurisetti/BikeSharing/blob/main/screenshots/UserTripsByGenderByWeekday.png" width=400 />

## NYC Story Boards
 A story board has been created to neatly display and present the entire information into one story board
<img src="https://github.com/hsurisetti/BikeSharing/blob/main/screenshots/NYCStory.png" width=400 />

## SUMMARY 
  Based on the above reports and statistics , we can see that bike sharing servicce is remarkably popular and busy in metroplitan cities. The user base is mostly male subscribers who use the service most frequently. The main usage is mostly around the morning and evening commute times.

## Some additional visualizations which would be helpful are :

### Top starting stations by Number of Rides
  The top 10 stations shows that each of them had atleast made more than 11 K rides

<img src="https://github.com/hsurisetti/BikeSharing/blob/main/screenshots/TopStartingStations.png" width=400 />

### Top Stations Map
   A map has been created to show the top stations visually in those respective locations.The top station where the trips made are more than 10,000 is mostly located in lower Manhattan.
 
<img src="https://github.com/hsurisetti/BikeSharing/blob/main/screenshots/TopStationsMap.png" width=400 />

### Top users by Age and Ride Duration
 The Top user group by ride duration mostly range from 25 to 35 years .There is an odd case where the data showed some spike around 50 years of age which might an exception for this case.

<img src="https://github.com/hsurisetti/BikeSharing/blob/main/screenshots/TripDurationByAge.png" width=400/>

### Number of rides per day

<img src="https://github.com/hsurisetti/BikeSharing/blob/main/screenshots/NumberofRidesPerDay.png" width=400 />

### Summary Description :

- Common Gender using this service : Male
- Common Age range : 25- 35 years
- Popular Station : Lower Manhattan
- Ride duration : Less than 30 minutes
- Peak Hours : Work hours.7 AM- 9 AM and 4 PM - 7 PM
- Bike Usage : Average of 6 times per day
- Users : Subscribers
 
## Some suggestion for future analysis involve, 
  - Comparing the data for different months to determine trends across the year
  - Including weather data would help in finding correlation between the two as to how whether might influence/ change the bike sharing.


