Data Analyst Pairing Exercise
==============================


# The Task

The task involves ingesting, cleaning and analysing some flight data using the provided data sources (CSV & JSON files). 


### Tasks:

we would like to explore and process the flights data in order to answer the following questions:
- how much time does the flights table cover ?
- how many departure cities the flight database covers ?
- which airplane manufacturer incurred the most delays in the analysis period ? (Explain how you decided upon the interpretation of 'most delays' and the implications on this on your results)
- what are the two most connected cities? (Again, explain how you arrived at the definition of 'most connected')
- what are the chances of planes flying out of JFK in poor weather getting delayed?


### The input data sources are comprised of (csv and json files in data.tar.gz):

- airlines
- airports
- flights
- planes
- weather


# Extra Credit
A loyalty programme has launched containing customer data in JSON format. 
How can we use this customer data alongside the above data to enable this program ?


# Acknowledgements
The flight delay and cancellation data was collected and published by the DOT's Bureau of Transportation Statistics.  
the files in data tarball are sourced from the following repos:

https://raw.githubusercontent.com/hadley/nycflights13/master/data-raw/airlines.csv
https://raw.githubusercontent.com/hadley/nycflights13/master/data-raw/airports.csv
https://raw.githubusercontent.com/hadley/nycflights13/master/data-raw/planes.csv
https://raw.githubusercontent.com/hadley/nycflights13/master/data-raw/weather.csv  
https://github.com/rich-iannone/so-many-pyspark-examples/raw/master/data-files/nycflights13.csv (renamed to flights.csv)
