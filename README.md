# Google-Maps-API

Application that uses the Google Maps API (dev).  This application shows the Google Maps view (zoom: 10) of San Francisco.  San Francisco, South San Francisco, and Daly City have markers that show their name when clicked on.  A custom icon is used for San Francisco.  An event listener is placed to show the content (City name) when clicked.  A function called addMarker() takes in parameter of props.  Props contain an object of coords (object of latitude and longitude), iconImage (custom icon if provided), and content (h1 tag with city name).  A new marker can be placed when clicked on by getting the google.maps.event.latLng data.  

Note: Cannot save new markers as there is no database to keep in.

JS & Google Maps API were mainly used.
