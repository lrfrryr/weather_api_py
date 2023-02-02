# Weather API
Created my own REST API that sends data to different endpoints that can be viewed through a Flask site.

## General Overview
I decided to make this project to gain a better understanding of how APIs work. I used a dataset of weather observations gathered by stations across Europe for the last century that I found online for the sake of simplicity, which I explored with the pandas library. The main page contains the information needed to use the API and how to build the different endpoints that fetch the data that the user is looking for.

### Points I would like to improve
- Make the Flask website more aestethically pleasing
- Construct the endpoints automatically so the user doesn't have to type them entirely
- Use all the data that the dataset provides by adding more endpoints

#### How to use the project
Clone repository and install needed packages. Open directory on console and type: flask --app main --debug run


<img src="weather_api.gif"/>
