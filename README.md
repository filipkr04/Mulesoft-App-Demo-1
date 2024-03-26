App connects to GeoDB cities API: https://rapidapi.com/wirefreethought/api/geodb-cities/ 
and returns list of first 5 cities, places or countries 

In order to use this API you have to make GET HTTPS request with header called searching.
Example headers are: cities, places, countries

Example request for cities: curl --location 'localhost:8081/geo' \
--header 'searching: countries'

Example request for places: curl --location 'localhost:8081/geo' \
--header 'searching: places'

Example request for cities: curl --location 'localhost:8081/geo' \
--header 'searching: cities'
