# Open Classrooms Projects
Collection of validated projects for the Open Classrooms' Front End Developer Path.


## Project 1: Restaurant Review Site

The project's goal is to create an easy-to-use, simple service that offers reviews of restaurants around a user's area.
The project uses Google Maps and Google Places API for live data. The deliverable is a single page application written in React JS.

The app has 2 main sections:
 - A Google Maps map loaded with the Google Maps API
   The Google Maps map will focus immediately on the position of the user, using the JavaScript geolocation API.
   A special color marker is shown at the user's current location.
 - A list of restaurants on the right side of the page that are within the area displayed on the map.
   Each restaurants is shown on the map based on their GPS coordinates.
   Restaurants that are currently visible on the map is displayed in list form on the side of the map with average reviews of each restaurant (ranging from 1 to 5 stars).

Other features:
 - When you click on a restaurant, the list of reviews is shown. Also show the Google Street View photo via the corresponding API! 
 - A filter tool allows the display of restaurants that have between X and Y stars. The map is updated in real-time to show the corresponding restaurants.
 - Add a review about an existing restaurant. Once a review or restaurant has been added, it appears immediately on the map.
 - Add a restaurant by clicking on a specific place on the map. A new marker will show the position of the new restaurant.

All information will not be saved if the user leaves the page (it will just be saved in memory for the duration of the visit).


Presentation: [Google Slide](https://drive.google.com/file/d/14YV1zIYRDK4NsKXDSpzFAMi8YZJjT4LK/view?usp=sharing)


**Acquired skills & tools:**
 - Develop a full React JS application according to a specification.
 - Debug an application using DevTools.
 - Use an external API in JavaScript.
 - Use Bootstrap CSS to make a responsive UI.

**Please note that the Google Maps API key used in this app has been deleted. In order to build the app, it is required to use a new Google API key.**
