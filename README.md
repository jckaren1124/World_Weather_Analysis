# World_Weather_Analysis

## Retrieve Weather Data

Retrieved weather information from random cities worldwide from OpenweatherMap API and created a new DataFrame: city_data_df.
![image](https://user-images.githubusercontent.com/89353378/139321089-e81f826e-d221-4d6e-9660-67204a883522.png)

Exported this DataFrame as a csv file: WeatherPy_Database.csv.
![image](https://user-images.githubusercontent.com/89353378/139321777-f46a96fd-698d-4525-97fa-22c26b233575.png)


## Create a Customer Travel Destinations Map

Input statements are in place for customer to enter weather temperature perferences during vacation destination search.
Minimum temperature of 60 and maximum temperature of 85 are entered as an example.
![image](https://user-images.githubusercontent.com/89353378/139323071-f5f49dae-3752-44c2-9f47-fc2049540e9a.png)

A cleaned version of city data set from the above parameters are retrieved and entered into a new DataFrame: updated_preferred_cities_df.
![image](https://user-images.githubusercontent.com/89353378/139323658-883c1ce2-45fb-4367-a79d-e4dfdc8e9390.png)

Hotel names are retrieved from the above cities, cleaned and added to the DataFrame.
![image](https://user-images.githubusercontent.com/89353378/139324642-f3da52e2-96eb-4e50-8153-e3e74f13d3bb.png)

Through the GoogleMap API, an interactive marker layer map with pop-up markers for the preferred cities was created with hotel and weather information. 
![image](https://user-images.githubusercontent.com/89353378/139324844-73f660b7-3254-4039-a758-d36b425d22c1.png)

This marker layer map is also saved in the "Vacation_Search" folder, and the data was exported to a csv file: WeatherPy_vacation.csv.
![image](https://user-images.githubusercontent.com/89353378/139326511-64b7fbbc-e893-4078-ba0e-e5ab62985c81.png)

## Create a Travel Itinerary Map

Four hotels in different cities in the United States were selected to be on the travel itinerary.  Four separate DataFrames were created for each city.
![image](https://user-images.githubusercontent.com/89353378/139327171-fc6ecb34-13b1-47cb-9457-0e5fa6536657.png)
![image](https://user-images.githubusercontent.com/89353378/139327208-e78bbb59-606b-4568-922d-4d41eef98fc8.png)
![image](https://user-images.githubusercontent.com/89353378/139327259-9cc20f7c-068a-40bf-ba51-3eebcb00ede1.png)
![image](https://user-images.githubusercontent.com/89353378/139327324-924ad594-c705-4fcd-88ce-b2ec5a817c3e.png)

The latitude and longitude pairs of each city was retrieved to create a directions layer map between the cities through GoogleMap API.
![image](https://user-images.githubusercontent.com/89353378/139327808-c8cfe3e7-d4a4-4436-af42-71d0c7c327de.png)
![image](https://user-images.githubusercontent.com/89353378/139327896-7ee97761-c7c7-4fda-b1ea-978805598516.png)

The DataFrame of all four cities are combined together into one DataFrame (itinerary_df) to create an interactive map with pop-up markers for each city on the itinerary through the GoogleMap API.
![image](https://user-images.githubusercontent.com/89353378/139328277-7c32dabd-0aae-4921-800d-c33ca03ffd84.png)
![image](https://user-images.githubusercontent.com/89353378/139328784-ea4e19ce-af0e-482d-8f63-0dcfeb94bee1.png)

These images are also saved on the Vacation_Itinerary folder.
![image](https://user-images.githubusercontent.com/89353378/139330256-079197c4-ab8a-4dfb-8211-d04ed3c06077.png)

