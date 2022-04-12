# Hotel-Recommendations
## Weather Analysis: 
* Gather Weather data from *OpenWeatherMap API*
* **Plotting:** Latitude against Maximum Temperature, Humidity, Cloudiness and Wind Speed
* **Linear Regression:** Latitude against Maximum Temperature, Humidity, Cloudiness and Wind Speed grouped by Northern and Souther Hemisphere
* **Conclusion:** 

  -There is a negative correlation for the Northern Hemisphere Latitude and Max Temp
  <img src="https://github.com/laurenbayson/Hotel-Recommendations/blob/main/Figures/north_maxtemp_corr.png" width="600" height="500">
 
  -There is a positive correlation for the Southern Hemisphere Latitude and Max Temp

  <img src="https://github.com/laurenbayson/Hotel-Recommendations/blob/main/Figures/south_maxtemp_corr.png" width="600" height="500">
)
 ## Hotel Recommender:
 * Takes city, country, date, latitude and longitude, etc.  from Weather Analysis
 * Asks user for maximum and minimum temperature desired for their vacation
 * Lists hotels within desired temperature using gmaps
