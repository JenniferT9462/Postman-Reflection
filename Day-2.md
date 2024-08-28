# Exploring the Weather API

## My Weather Service-Base URl

<https://api.weatherbit.io/v2.0/>

##  Query Parameters:

  * key=[your API key] (REQUIRED)
  * ?current or ?forecast/daily 
  * Change units from default metrics
        &units=S - Scientific (Kelvin, m/s, mm)
        &units=I - Fahrenheit (F, mph, in) 
  * Get observation by city name
        &city=Raleigh&country=US
        &city=Raleigh,NC
        &city=Raleigh,North+Carolina

  * Get observation by postal code
        &postal_code=27601&country=US

## Screenshot

![Weatherbit in Postman](<img/weatherbit.png>)

## Observations from my GET Request:

* temperature: "app_temp": 98.3
* weather conditions: "weather": 
                        "description": "Overcast clouds"
* location details: "lat": 30.45075
                    "lon": -91.15455

Note any status codes returned with the response and what they signify.

## Reflect on Query Parameters:

    The API key is required to access certain API requests. In this case, we are using a weather API that requires an account with a unique access key. Some APIs parameters are different so it is important to have them set correctly. When  I was using Postman I misspelled 'forecast' and I got an error saying that 'forecast is not a function of this API'.





