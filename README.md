# Hotel-Recommendations
## [Weather Analysis](https://github.com/laurenbayson/Hotel-Recommendations/blob/main/weather_analysis.ipynb): 
* Gather Weather data from *OpenWeatherMap API*
* **Plotting:** Latitude against Maximum Temperature, Humidity, Cloudiness and Wind Speed
* **Linear Regression:** Latitude against Maximum Temperature, Humidity, Cloudiness and Wind Speed grouped by Northern and Souther Hemisphere
* **Conclusion:** 

  - There is a negative correlation for the Northern Hemisphere Latitude and Max Temp
  <img src="https://github.com/laurenbayson/Hotel-Recommendations/blob/main/Figures/north_maxtemp_corr.png" width="550" height="400">
 
  - There is a positive correlation for the Southern Hemisphere Latitude and Max Temp

  <img src="https://github.com/laurenbayson/Hotel-Recommendations/blob/main/Figures/south_maxtemp_corr.png" width="550" height="400">

 ## [Hotel Recommender](https://github.com/laurenbayson/Hotel-Recommendations/blob/main/hotel_search.ipynb):
 * Takes city, country, date, latitude and longitude, etc.  from Weather Analysis
 * Asks user for maximum and minimum temperature desired for their vacation
 * Lists hotels within desired temperature using *Google Maps API*
    - Example input – Minimum Temp: 80F and Maximum Temp: 110F
 <img src="https://github.com/laurenbayson/Hotel-Recommendations/blob/main/Figures/hotel%20data.png" width="650" height="500">
 <img src = "https://github.com/laurenbayson/Hotel-Recommendations/blob/main/map%20(1).png">
