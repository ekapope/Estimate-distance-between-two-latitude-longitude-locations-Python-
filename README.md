# Estimate distance between two latitude/longitude locations (Python)

Since there is a limit qouta for Google API daily requests, so I decided to use manual calculation for the distance between two points on the map. Please note that the term 'distance' in this project is actually 'displacement'. It only measures from its starting position to the final position regardless the actual walkable path. 

This is the subsequent project after getting the coordinates from Google Map - Geocoding API. Calculate the distance between two locations, in this case, condos to metro stations. 

Previous project link:
https://github.com/ekapope/Retrieve-GPS-location-using-google-map-api

The result is the list of closest metro stations and distance in meters to each property. 

The actual commutable path can be obtained using Google Distance Matrix API, example via this link. https://github.com/ekapope/Estimate-distance-between-two-locations-using-Google-Distance-Matrix-API
