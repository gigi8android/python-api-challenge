# python-api-challenge

### Homework Submission
The submission pack is included:
1. *Jupyter notebooks: scrap_WeatherPy_final and scrap_VacationPy_final.* 
    - *Note*: A sleep clock is set when performing API calls for part1 WeatherPy. API calls will be put on sleep for 60 seconds when a set of 50 cities had been called. A notification message "Data Retrieval Completed" will be displayed on screen when all calls are done. Please refer to the comments embedded in the notebooks for more details.
2. *Output folders:* 
    * *Folder called output_data:* contains csv file that exported from Part1 - WeatherPy (to be used in Part2 - VacationPy)
    * *Folder called output_images:* contains graphs & images exported from Part1 & Part2 of the homework. The heatmap of VancationPy will be exported in html format and hence it won't be displayed appropriately in the jupyter notebook, please open it in the browser instead.
3. *An empty file called api_keys.py* - where api keys for the openweatherMap and google should be stored. This file must be updated with the valid keys prior running the jupyter notebooks, otherwise the programs will be crashed.

### Data analysis/ observations: 
- In the scatter graph "Latitude vs Temperature", it appears that there's a strong corelation between these 2 elements as the dots are mostly groupping together, i.e. less spreading apart. The dots in the scatter graphs "Latitude vs Wind Speed" and "Latitude vs. Humidity" are also showing that potentially there are some kind of relationship between them. Whereas the dots in the scatter graph "Latitude vs Cloudiness" are spreading everywhere.
- There are corelation values for "Latitude vs Cloudiness" for both Nothern and Southern Hemispheres, but their data are broad spreading, too many outliers in the graphs with inconsistent data points. It may lead to the question that whether there's actually a relationship between two of them or there's another factor in play that has not yet been identified.
- Based on the linear regressions in the graphs "Temperature vs Latitude", it shows that there is a negative corelation between these two elements in Northern Hemisphere, however it shows positive corelation in the Southern Hemisphere. The findings look contrast to each other but actually showing the same outcome. Both of them demonstrate that the further away from the Equator the lower the temperature is.
- There is very weak negative (or near zero) correlation between the Wind Speed and Latitude in Northern Hemisphere but it gets tronger (i.e. higher negative r-value) in Southern Hemisphere.
- When analysing all the graphs, it is observed that there is a strong relationship between latitude, temperature and wind speed. It illustrates the fact that in the south, near the Equator, the sun warms the water and land. Warm equatorial air rises higher into the atmostsphere and migrates toward the poles creates a low-pressure system. At the same time, cooler, denser air moves over Earth’s surface toward the Equator to replace the heated air creates a high-pressure system. Winds generally blow from high-pressure areas to low-pressure areas.
