# Exploring the Weather API

## My Weather Service-Base URl

<https://api.weatherbit.io/v2.0/>

* /current or /forecast/daily 

##  Query Parameters:

  * ?key=[your API key] (REQUIRED)
  * Change units:
      - &units=M - Metrics(default)
      - &units=S - Scientific (Kelvin, m/s, mm)
      - &units=I - Fahrenheit (F, mph, in) 

  * Get observation by city name:

      - &city=Raleigh&country=US
      - &city=Raleigh,NC
      - &city=Raleigh,North+Carolina

  * Get observation by postal code:

      - &postal_code=27601&country=US

## Screenshot

![Weatherbit in Postman](<img/weatherbit.png>)

## Observations from my GET Request:

* temperature: 
  - "app_temp": 98.3
* weather conditions: 
  - "weather": 
      - "description": "Overcast clouds"
* location details: 
  - "lat": 30.45075
  - "lon": -91.15455

Note any status codes returned with the response and what they signify.

## Reflect on Query Parameters:

The API key is required to access certain API requests. In this case, we are using aweather API that requires an account with a unique access key. Some APIs parameters are different so it is important to have them set correctly. When I was using Postman I misspelled 'forecast' and I got an error saying that 'forecast is not a function of this API'. 

Also, parameters are used to request more specific data like, city, zipCode or state ID. Or, to change the units of measurements that the data will use. When, requesting images from somewhere like Pexels, you can set parameters for height, width, sepia and more. 





