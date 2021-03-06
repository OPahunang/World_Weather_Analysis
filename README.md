# World_Weather_Analysis

## Overview:

PlanMyTrip is a travel technology company that specializes internet related services in hotel and lodging industry. 

The goal is to collect and present data from customer input,  via search page, on which they filter based on preferred travel criteria in order they find their ideal travel plan anywhere in the world.  


## Results:

### Deliverable 1: Retrieve Weather Data

-Retrieve all of the following information from the API call:

   •	Latitude and longitude
   •	Maximum temperature
   •	Percent humidity
   •	Percent cloudiness
   •	Wind speed
   •	Weather description 


 ![Resources/Retrieve_information_from_API.png](https://github.com/OPahunang/World_Weather_Analysis/blob/main/Weather_Database/Resources/Retrieve_information_from_API.png)


-Add the weather data to a new DataFrame

   ![Add_weather_data_to_new_dataframe.png](https://github.com/OPahunang/World_Weather_Analysis/blob/main/Weather_Database/Resources/Add_weather_data_to_new_dataframe.png)


-Export the DataFrame as WeatherPy_Database.csv  into the Weather_Database folder

   ![Resources/Export_dataframe.png](https://github.com/OPahunang/World_Weather_Analysis/blob/main/Weather_Database/Resources/Export_dataframe.png)


### Deliverable 2: Create a Customer Travel Destinations Map

-Input statements are written to prompt the customer for their minimum and maximum temperature preferences.

   ![Input_Statement_min_max_temperature.png](https://github.com/OPahunang/World_Weather_Analysis/blob/main/Vacation_Search/Resources/Input_Statement_min_max_temperature.png)


-A new DataFrame is created based on the minimum and maximum temperature, and empty rows are dropped.

   ![DataFrame_created_min_max_temperature.png](https://github.com/OPahunang/World_Weather_Analysis/blob/main/Vacation_Search/Resources/DataFrame_created_min_max_temperature.png)


-The hotel name is retrieved and added to the DataFrame, and the rows that don’t have a hotel name are dropped.

   ![Hotel_name_retrieved_and_drop_hotel_without_name.png](https://github.com/OPahunang/World_Weather_Analysis/blob/main/Vacation_Search/Resources/Hotel_name_retrieved_and_drop_hotel_without_name.png)


-The DataFrame is exported as a CSV file into the Vacation_Search folder and is saved as WeatherPy_vacation.csv. 

   ![Dataframe_exported_as_CSV.png](https://github.com/OPahunang/World_Weather_Analysis/blob/main/Vacation_Search/Resources/Dataframe_exported_as_CSV.png)


-A marker layer map with pop-up markers for the cities in the vacation DataFrame is created, and it is uploaded as a PNG. Each marker has the following information: 
   
   •	Hotel Name
   •	City
   •	Country
   •	Current weather description with the maximun temperature
   
   ![Resources/Map_marker_layer.png](https://github.com/OPahunang/World_Weather_Analysis/blob/main/Vacation_Search/Resources/Map_marker_layer.png)


### Deliverable 3: Create a Travel Itinerary Map

-Four DataFrames are created, one for each city on the itinerary

   ![Four_Dataframes_each_city.png](https://github.com/OPahunang/World_Weather_Analysis/blob/main/Vacation_Itinerary/Resources/Four_Dataframes_each_city.png)


-The latitude and longitude pairs for each of the four cities are retrieved.

   ![Lat_Lng_for_each_city.png](https://github.com/OPahunang/World_Weather_Analysis/blob/main/Vacation_Itinerary/Resources/Lat_Lng_for_each_city.png)


-A directions layer map between the cities and the travel map is created and uploaded as WeatherPy_travel_map.png.
  
  ![WeatherPy_travel_map.png](https://github.com/OPahunang/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)
  
  
-A DataFrame that contains the four cities on the itinerary is created.
   
   ![Resources/Dataframe_concat.png](https://github.com/OPahunang/World_Weather_Analysis/blob/main/Vacation_Itinerary/Resources/Dataframe_concat.png)
   

-A marker layer map with a pop-up marker for the cities on the itinerary is created, and it is uploaded as WeatherPy_travel_map_markers.png. Each marker has the following information: 

   •	Hotel name
   •	City
   •	Country
   •	Current weather description with the maximum temperature
   
   
![WeatherPy_travel_map_markers.png](https://github.com/OPahunang/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)




