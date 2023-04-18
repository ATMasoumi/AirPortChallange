# ``AirPortChallenge``

The purpose of this challenge is designing and developing an application representing a list of airports near a specified geo-coordinate given by the user.

## Overview

The application uses Amadeus: https://developers.amadeus.com/get-started/get-started-with-self-service-apis-335  as network source for APIs. It’s recommended to checkout the documentation for making API calls. You need to get an API KEY in order to call API services. (See Authorization guide : https://developers.amadeus.com/self-service/apis-docs/guides/authorization-262 ) Turn on your VPN when sending API calls.


## Two screens:
A. First, getting a sample location coordinate (latitude and
longitude).
B. Second, showing a list of airports in radius of 1000 Km
consist of 20 items pagination per page.

## Items in the list should have the ability to be sorted by:
A. Relevance
B. Distance
C.Flights Score 
D.Travelers Score

## Each item on the list should have shown followings fields:
1. Name + City
2. Distance + Unit
3. IATA Code
4. TimeZone offset


One and only needed API is:
Base URL: test.api.amadeus.com/v1/reference-data/locations/airports

check out the doc here: https://developers.amadeus.com/self-service/category/air/api-doc/airport-nearest-relevant/api-reference
