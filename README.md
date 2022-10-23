# AutoTour: calculate and plot paths through bicycle stations within a city.
![image](https://github.com/apsears/AutoTour/blob/main/web/images/mega_0.jpg)

This notebook calculates optimal routes through several waypoints using Google Maps. Circuits are limited to about 26 stations (1 start = endpoint + 25 waypoints). You must have a Google Maps project and API token. Store this token in a json file named `token.json`

The repo includes data, figures, and html files for a set of circuits around all 157 Houston BCycle stations for the #TourdeBCycle
The data is accurate as best as I can determine as of October 2022. The html pages are useful because they include links that invoke Google or Apple maps directions to the GPS of the next station.


For demo, see http://adamsears.net/tourdebcycle/big.html
