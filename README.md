# Geocoder

**NOTE:** The accuracy of the geocoding and reverse geocoding is not guaranteed to be 100% perfect by Google, and the geolocation of HTML5 may not be perfect either. These results are the best estimations -- they may not always be flawless. 

This is the repo for a web page I made purely to play around with Google Map's Javascript API. 

The webpage will prompt you to allow access to your geolocation. This will be used to display your current
location on Google's map object. HTML5 allows for accessing a user's geolocation through the getCurrentPosition() function.

Geocoding is used through three input boxes below the map for Street Address (including #), City, and State. Because this utilizes Google's search methods, not all three components of the address must be filled. Generally, street address should always be filled. Upon submitting the information, a marker will be generated on the corresponding location with the latitude & longitude included in the information box (which is shown when marker is clicked) of the marker object. The (lat,lng) is also shown below the inputs in red text. 

Reverse Geocoding is used when you click a point on the map -- the (lat,lng) will be retrieved and reverse geocoded, then the address parts will be filled into the corresponding input box as a form of feedback to the user. 

*All references used for this*

[Geocoding Overview](https://developers.google.com/maps/documentation/geocoding/start?refresh=1)
[Geocoding Reference](https://developers.google.com/maps/documentation/geocoding/intro)

