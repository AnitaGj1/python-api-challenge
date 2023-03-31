# python-api-challenge

## Part 1: WeatherPy

I've created a Python script to visualize the weather of over 500 cities of varying distances from the equator. I've used the citipy Python library, the OpenWeatherMap API, and I've created a representative model of weather across cities.

### Created scatter plots:

* ## Latitude vs. Temperature

![Lat vs  Max Temp](https://user-images.githubusercontent.com/122633144/229183456-c18f5c0d-f313-4b74-a8fb-58a715b83674.png)

* ## Latitude vs. Humidity

![Lat vs  Humidity](https://user-images.githubusercontent.com/122633144/229183557-146502d1-a232-446d-a3be-fdc27267fbf3.png)

* ## Latitude vs. Cloudiness

![Lat vs  Cloudiness](https://user-images.githubusercontent.com/122633144/229183606-3dcf9420-4fd9-4007-b6a6-e05b6b261d50.png)

* ## Latitude vs. Wind Speed

![Lat vs, Wind](https://user-images.githubusercontent.com/122633144/229183643-489390d1-6f36-4665-ace6-da3d10d58219.png)

###  Linear Regression for Each Relationship separating the plots into Northern Hemisphere and Southern Hemisphere. Created plots:

* ## Northern Hemisphere: Temperature vs. Latitude

![lat vs  max temp North](https://user-images.githubusercontent.com/122633144/229184439-37985914-2460-44ca-b7c5-b037150ee4ff.png)

* ## Southern Hemisphere: Temperature vs. Latitude

![lat vs msx temp south](https://user-images.githubusercontent.com/122633144/229184525-3d965cef-ea04-4d5f-abc6-55138bcdf8e5.png)

**Discussion** 

In a city latitude vs temperature relationship, a linear relationship refers to how the temperature changes as the latitude of the city changes. Looking at the city latitude vs temperatute relationship, the r-values 0.769 for the northern hemisphere and 0.561 for the southern hemisphere, indicates moderate positive linear relationship between the two variables, meaning that as the city latitude increases/decreases, so does the temperature.

* ## Northern Hemisphere: Humidity vs. Latitude

![lat vs humidity North](https://user-images.githubusercontent.com/122633144/229184579-f1f1ae65-dce9-4e6a-9a6b-91b13c731678.png)

* ## Southern Hemisphere: Humidity vs. Latitude

![lat vs hunidity south](https://user-images.githubusercontent.com/122633144/229184630-4b1ac5c1-fa11-4ec1-adb9-eb4ae287624c.png)

**Discussion**

In a city latitude vs humidity relationship, a linear relationship refers to how the humidity changes as the latitude of the city changes. Looking at the city latitude vs humidity relationship, the r-values 0.155 for the northern hemisphere and 0.038 for the southern hemisphere, indicates that there is a weak positive correlation between the two variables, meaning that as the city latitude increases, the humidity tends to increase slightly as well.

* ## Northern Hemisphere: Cloudiness vs. Latitude

![lat vs cloudines north](https://user-images.githubusercontent.com/122633144/229184685-41bd5725-cd31-4778-9cb0-d551ce68c5e0.png)

* ## Southern Hemisphere: Cloudiness vs. Latitude

![lat vs cloudiness south](https://user-images.githubusercontent.com/122633144/229184776-d8477d60-ec8e-4aea-88bb-d5b7d5ff84c7.png)

**Discussion:**

In a city latitude vs cloudiness relationship, a linear relationship refers to how the cloudiness changes as the latitude of the city changes. Looking at the city latitude vs cloudiness relationship, the r-values 0.018 for the northern hemisphere and 0.032 for the southern hemisphere, indicates that there is a very weak positive correlation between the two variables, meaning that as the city latitude increases, the cloudiness tends to increase very slightly.

* ## Northern Hemisphere: Wind Speed vs. Latitude

![lat vs wind north](https://user-images.githubusercontent.com/122633144/229184815-f862cc86-3bc0-446a-aefa-b1a9512ed619.png)

* ## Southern Hemisphere: Wind Speed vs. Latitude

![lat vs wind south](https://user-images.githubusercontent.com/122633144/229184840-42de79b7-e8d8-46f8-aecb-d6d262f425ed.png)

**Discussion**

In a city latitude vs wind speed relationship, a linear relationship refers to how the wind speed changes as the latitude of the city changes. Looking at the city latitude vs wind speed relationship, the r-values 0.010 for the northern hemisphere and 0.073 for the southern hemisphere, indicates that there is a very weak positive correlation between the two variables, meaning that as the city latitude increases, the wind speed tends to increase only slightly, if at all.


## Part 2: VacationPy

I've created a map that displays a point for every city from the previous data frame, where the size of the point is the humidity in every city.

![bokeh_plot1](https://user-images.githubusercontent.com/122633144/229186672-96d6f27a-7c1c-4e7b-8aee-40d7800b5586.png)

After adjusting my specifications to find my ideal weather conditions (Temperature between 20 and 35 Celzius degrees, and humidity 40-70%), I've created the map only with the cities that fit my specifications and added the nearby hotel as information.

![bokeh_plot](https://user-images.githubusercontent.com/122633144/229185896-c45b88ac-da4b-46cb-97ad-a0ae074e4ad2.png)
