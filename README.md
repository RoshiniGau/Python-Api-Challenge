## Python-Api-Challenge - What's the Weather Like

# Background 
The repo contains two notebooks WeatherPy- explores the way weather changes as we approach the equator - and VacationPy - plan future vacations given ideal weather conditions worldwide . 

# Part 1 - WeatherPy
In this example,created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, utilizied a simple Python library, the OpenWeatherMap API.
* First objective was to build a series of scatter plots to showcase various relationships.
* Second objective was to run linear regression on each relationship, only this time separating them into Northern and Southern hemisphere.

# Part 11 - VacationPy
 Worked with weather data to plan future vacations. Used jupyter-gmaps and the Google Places API for this part of the assignment.
 * Created a heat map that displays the humidity for every city from WeatherPy notebook
 * Filtered the dataframe to find ideal weather 
 * Used Google Places Api to find the first hotel for each city located within 5000 meters of the coordinates in the dataframe 
 * Created a map of the hotels on top of the humidity heatmap with each pin containing the Hotel Name ,City and Country
 
 #Analysis and Observation
 
* Of the weather measures examined versus changes in latitude the strongest correlation was found between Northern Hemisphere changes in latitude versus temperature . This relationship has a high r-squared of 0.45 meaning 45% of the variance in this data . Of the other relationship examined there is some weak correlations .
* Southern Hemisphere climates tend to be slightly milder than those at similar latitudes in the Northern Hemisphere. This is because the Southern Hemisphere has significantly more ocean and much less land; water heats up and cools down more slowly than land
* Highest temperature is found at 0 latitude and as the latidude increases or decreases, temperature drops. This happens as equatorial region receives sunlight straight with less or no angle due to curvature shape of earth.
* Latitude doesn't have a strong iinfluence on wind speed. The speed of the wind is controlled by the strength of the air pressure gradient, the stronger the pressure gradient the higher the wind speed.




