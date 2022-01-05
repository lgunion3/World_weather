# World Weather Analysis using APIs
## Overview
I created an application that enables end users to input the minimum temperature and maximum temperature values that will generate a list of cities satisfying the two values. The output for the end user include, hotel name, max temp, a Gmpas and location of the cities that satisfy input values. Gmaps API and the OpenWeatherMaps API enabled the creation of this application.
### Preprocessing
For both Gmaps and OpenWeatherMaps APIs I created accounts for a personal API key. Due to the sensitivity of the API keys, I modified my .gitinore code and imported the APIs variables into the application's code. 
## Results

#### Weather Database
This database was created to generate random city locations. Weather details were input into a DataFrame. This DataFrame populates the weather when the end user inputs their maximum and minimum temperature points. 

#### Vacation Search
The cities on the map are all cities with hotels. The cities that populate must be within the minimum and maximum values provided by the users input. 
![WeatherPy_vacation_map](https://user-images.githubusercontent.com/87162266/137606149-743a2cd3-9f5f-43cc-96e9-9868cc68ba08.png)

#### Vacation Itinerary
A travel itinerary is created using four cities that match the end user's potential travel destinations. The markers will show the hotel name, city, country, weather description and maximum temperature.
<img width="334" alt="WeatherPy_travel_map" src="https://user-images.githubusercontent.com/87162266/137606147-65711f63-3762-4861-b160-22a6a9e2048d.png">
