### Weather_API with flask
This projects allows the users to retrieve the information which contains the current weather information for multiple locations, this data is taken with the help of generated API key which was generated using OpenWeatherMap API.

## Brief Procedure
Install the required libraries.
To run the program we need to generate the API key using the OpenWeatherMap API key.
Run the application , once the code is compiled , open the Postman and create a new request to http://127.0.0.1:5000/weather with the GET method.
Add a query parameter 'city' with the value being the city.
For example (city=Davangere).
Once its done , send the request and get the output.To check the accuracy of the Output which contains the weather data by OpenWeatherMap.

 ## screenshot
![Screenshot 2023-11-28 153253](https://github.com/Sanjay19200/WeatherApi/assets/136919818/337ed415-6e21-4dca-ac0f-998b2ee87839)

![Screenshot 2023-11-28 153426](https://github.com/Sanjay19200/WeatherApi/assets/136919818/dc35dd63-5601-4eaa-b013-ac4386d9c818)

![image](https://github.com/Sanjay19200/WeatherApi/assets/136919818/f4bf6608-4d5e-4ac1-881b-cbdf711d5034)

## Additionals
The code includes the ability to retrieve weather information for multiple locations through the /weather endpoint , and even the code has try-except blocks to catch and handle exceptions which may occur during the API requests.




