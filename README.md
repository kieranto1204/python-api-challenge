Use gitbash to clone this repository for the highest chance at succeeding at running the data.

Make sure you have your own api_key for these resources and to put them into a file called api_keys.

This challenge came in two parts:

1. WeatherPy
   We were to use the citipy python library and the OpenWeatherMap API to generate scatter plots that showed the relationship between several weather variables and Latitude:
     Latitude vs Temperature, Humidity, CLoudiness, Wind Speed
   After creating those scatter plots, we then needed to compute the linear regression for each relationship and then, wrote brief explanations for what we observed about the correlation between latitude and those weather variables, based on their location in the northern or southern heimsphere.

   Finally, we also combpiled that data into a csv file to use for the second part of the challenge, which was the VacationPy

   (Do note that if you are running the code for the first time, that it will take upwards of 6 minutes for the program to finish scrapping all the weather data from the api)
2. VacationPy
   This challenge first had us create a map with points at each of the city locations calculated on the csv from the first challenge, we were then told to have the point size correlate with the amount of humidity.

   The second part of the challenge was to filter out cities with ideal weather conditions, that we decided ourselves (I just used the example values given in the instructions)

   Finally we were to use these filters to create a list of hotels that would meet our standards, and then recreated the initial map with these locations as points.

   In addition to the code from the class I also used:
   
   - https://hvplot.holoviz.org/user_guide/Introduction.html
   - https://www.digitalocean.com/community/tutorials/pandas-dropna-drop-null-na-values-from-dataframe
