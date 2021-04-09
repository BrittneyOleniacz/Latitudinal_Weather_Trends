# What's the Weather Like?

## Weather Models
### Objective 
"What's the weather like as we approach the equator?" Sure, it is common knowledge that it is warm at the equator and cold at the poles, but, how could we prove it? 
![Equator](Images/equatorsign.png)
### Tasks
1. Generate 500+, non-repeating cities across Earth based on latitude/longitude and varying distances from the equator by utilizing a [simple Python library](https://pypi.python.org/pypi/citipy)
2. Perform a weather check on each of the cities using a series of successive API calls from [OpenWeatherMap API](https://openweathermap.org/api)
3. Include a print log of each city as it's being processed with the city number and city name.
4. Create a series of scatter plots to showcase the following relationships across the cities:
    * Temperature (F) vs. Latitude
    * Humidity (%) vs. Latitude
    * Cloudiness (%) vs. Latitude
    * Wind Speed (mph) vs. Latitude
5. Seperate the cities by hemisphere and run linear regression on each relationship with an explanation of the model and observed relationships:
    * Northern Hemisphere - Temperature (F) vs. Latitude
    * Southern Hemisphere - Temperature (F) vs. Latitude
    * Northern Hemisphere - Humidity (%) vs. Latitude
    * Southern Hemisphere - Humidity (%) vs. Latitude
    * Northern Hemisphere - Cloudiness (%) vs. Latitude
    * Southern Hemisphere - Cloudiness (%) vs. Latitude
    * Northern Hemisphere - Wind Speed (mph) vs. Latitude
  * Southern Hemisphere - Wind Speed (mph) vs. Latitude
6. Save a CSV of all retrieved data and a PNG image for each scatter plot.
7. Provide written descriptions of three observable trends based on the data.

## Vacation Spot Selection
### Objective
Use jupyter-gmaps and the Google Places API for this part of the assignment.

### Tasks
1. Create a heat map that displays the humidity for every city.
2. Narrow down the DataFrame to find your ideal weather condition. For example:
   * A max temperature lower than 80 degrees but higher than 70.
   * Wind speed less than 10 mph.
   * Zero cloudiness.
   * Drop any rows that don't contain all three conditions. You want to be sure the weather is ideal.
3. Using Google Places API to find the first hotel for each city located within 5000 meters of your coordinates.
4. Plot the hotels on top of the humidity heatmap with each pin containing, at minimum **Hotel Name**, **City**, and **Country**.
  ![hotel map](Images/hotel_map.png)





