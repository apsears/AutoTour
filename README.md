# AutoTour
Automatically calculate and plot circuits through bicycle stations throughout a city.
![image](https://github.com/apsears/AutoTour/blob/main/web/images/mega_0.jpg)

This notebook calculates optimal routes through several waypoints using Google Maps. You must have a Google Maps project and API token.
Store this token in a json file named `token.json`

As is, it includes figures and html files for a set of circuits around all the Houston BCycle stations in Houston, for the #TourdeBCycle
The html pages are useful because they include links that invoke Google or Apple maps directions to the GPS of the next station.

Circuits are limited to about 26 stations (1 start = endpoint + 25 waypoints).

For demo, see http://adamsears.net/tourdebcycle/big.html
