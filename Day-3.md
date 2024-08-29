# API Collections

## Weatherbit base URL

<https://api.weatherbit.io/v2.0/>

  - I will be using  
    * /current or /forecast/daily
  - And 
    * &units=I - Fahrenheit (F, mph, in)
    * &city=New+York
    * &city=Phoenix
    * &city=Denver

## Steps to Creating a Collection & Environment
* Set up collection - add new collection '+'
* Name the collection
* Create a new environment for the new collection
  - Here you can set up variables for search params
    * 'key' and 'value'
  - And set up Authentication by saving your API key as a header or param
* Now you can add new request and your preset params and API key will be there as long as you are in the collection you want w/the environment selected. 

## Screenshots
### Creating a collection

![colection](<img/collection.png>)

### Setting up Your Environment

![environment](<img/enviroment.png>)

### Setting API key as a Variable

![API Key](<img/apiKey.png>)

### GET Request

![Request 1](<img/request.png>)

![Request 2](<img/request2.png>)

## Summary

Setting up a collection and an environment made things very easy to apply several requests using the same API. Through the weatherbit API I was able to see the data for any city and their forecasts as well as historical data which would be great for predicting weather patterns. You can look up severe weather alerts and air quality.