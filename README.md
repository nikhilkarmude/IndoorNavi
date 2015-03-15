IndoorNavi
===========

###Andriod Application for Indoor navigation using smart phone sensors and map of the building.
###### Key aspect of this project is: This application does not utilize any GPS or cellular data or WIFI.

The application consists of two major parts:

1. Showing path to user on map.
 - Creation of Database for maps.
 - Implementing the user interface.
 - Sensor services. 

2. Tracking the user to guide in directions.
 - Step counters sensors technique.

###Application Flow:
 - User scans the QR code. 
 - Corresponding Building map along list of important landmarks will show on map.
 - The user will select the destination from the landmark list or provide input using either voice or typing it. 
 - Route to the destination from starting location will be drawn on map. 
 - As the user walks the map will be updated showing the user location over the path.
 - As the user is required to take turn the application will prompt to take turn by voice.
 - As user reaches destination the application will stop.

###Assumptions:
 - User scans the QR code.
 - User starts from the starting location mentioned in map.
 - User follows the route in map.
 - There is a map available for each building which the app supports. 
 - User has latest android based smartphone. 






