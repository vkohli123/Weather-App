# Weather-App
This is a Weather App that uses API to get live weather information ,It uses a bootstrap framework for its design 


index.html:- 

This is an HTML file that creates a weather application interface.
 It uses Bootstrap CSS framework for styling and has a navbar with links to the home page, about page, and a dropdown menu with different city options.
 It also includes a search bar for searching for weather information of a particular city. The HTML file also includes several span tags with unique ids
 that are likely used to dynamically update the page with weather data from an external source.


script.js:- 
This is a JavaScript code snippet that defines a function called getWeather() that takes a city as its parameter. The function makes a GET request to an 
API endpoint to fetch weather information for the specified city, and includes two headers in the request: 'X-RapidAPI-Key' and 'X-RapidAPI-Host'. 
The response from the API is in json format and then it updates the innerHTML of several elements with specific ids 
(temp, feels_like, humidity, min_temp, max_temp, wind_speed, wind_degrees, sunrise, sunset) with the corresponding values from the response object.
It also updates innerHTML of cityname with the city passed to the function.

The function is also called with default city Delhi when the page is loaded.
Additionally, it also listens for a click event on the element with "Submit" id, when the element is clicked, it calls the getWeather(city.value) function with
 the city.value entered in the input field.
It uses fetch api to make the request, and it logs any error that might occur while fetching data.

untitled:-
This is a JavaScript code snippet that updates the innerHTML of several elements with specific ids
 (temp, feels_like, humidity, min_temp, max_temp, wind_speed, wind_degrees, sunrise, sunset) with the corresponding values from a response object. 
The response object is likely coming from an API call that fetches weather data. It's updating the values of these elements with the data coming 
from the API response.

![weather_1](https://github.com/vkohli123/Weather-App/assets/110954074/8a5d6ccd-9297-41ca-bd96-cc89680ec4bb)


![weather_2](https://github.com/vkohli123/Weather-App/assets/110954074/f0d4a8ce-1eb7-4060-98c6-1ea1a615d3b6)


