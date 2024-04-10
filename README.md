# python-api-challenge
Module 6 Challenge

In the first part of this challenge, we will be exploring different weather conditions in random cities across the world. We will be generating a list of random cities in a range of latitude and longitude coordinates, pulling information in regards to their humidity, cloudiness, wind speeds, and their max temperature for the day. With this information, we will be graphing our findings to see the correlation with the latitude. 
in the second part of this challenge, we will be taking the cities and their weather information and finding ideal vacation destinations based on my criteria. Once we are finished narrowing down our options, we will be finding the nearest hotel within that city.

Before getting started, please keep in mind that the information was pulled from OpenWeatherMap (https://api.openweathermap.org/data/2.5/weather?) and GeoAPIfy (https://api.geoapify.com/v2/places) using my own API keys. 

To run the program:
- If you have your own API keys for these sites, please paste them into <api_keys.py> and save the file. 

- We will first be running the program in <weather.ipynb>. --> the cities will be randomly generated
    If an error occurs (api_key is not defined), you will need to save <api_keys.py> a few times, restart the kernel in <weather.ipynb>      and then run the program again.
    
  *** you will see comments in the last section of the program in regards to the Regression plots, please keep in mind that these
      comments are explaining my findings with the cities that were randomly generated at the time of creation

  - <vacation.ipynb> is the program to be ran after <weather.ipynb> has finished to its completion.

  Once the second program has finished to its completion, you will be left with a map of the nearest hotels to the cities that have fallen into my criteria and we can finally start planning on a destination for vacation!
