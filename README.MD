# Description

This application is a single-page weather dashboard. It was created using HTML, CSS, Bootstrap CSS Framework, JavaScript, jQuery, and the font-awesome icon pack. The application uses jQuery AJAX calls to the Open Weather API to obtain weather and UV information. This dashboard allows the user to input a desired city, and will present the user with current weather conditions as well as a five day forecast.

## Features

Current weather conditions and five day forecast for a user selected city
UV index, with color coding based upon the severity of the exposure as defined by the US EPA
User searches are saved in localStorage for up to the last 10 cities searched
When the user reopens the application, it will display the last city searched in addition to a listing of previous cities searched
Clicking on a previous search button will redisplay the current weather and forecast for that city
The application will provide a warning to the user if the city entered into the search field does not match a city in the Open Weather API database

### Installation

Upload index.html, LICENSE, and assets folder to the deployed webserver. Assets folder contains JavaScript, CSS files, and images.

The application shown below was deployed using GitHub Pages. The repository can be replicated by via fork, clone, and redeployment with GitHub Pages.

#### Usage

Upon accessing the application for the first time, the user will only be presented with a search field where they can enter their desired city. After the first search, current weather, 5 day forecast, and a listing of previous searches will appear. Previous cities searched will be stored in localStorage and will be recalled the next time the user accesses the application.

link to the repo:
https://github.com/chukwuebukaace/Weather-Dashboard  
link to the deployed: website https://chukwuebukaace.github.io/Weather-Dashboard/

##### screenshot to the website:
![screenshot of the website](/images/IMG_0108.jpeg)