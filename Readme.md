# Transit Tango

This is an application built with Spring Boot in Java. It utilizes the Google Maps APIs along with the MARTA transit system API to search for nearby buses in the Atlanta, GA area.

## Usage

Clone the repo, supply an `application.properties` file with a Google API key, along with the following url properties:
```
transit_url = http://developer.itsmarta.com/BRDRestService/RestBusRealTimeService/GetAllBus

geocoding_url = https://maps.googleapis.com/maps/api/geocode/json?address=

distance_url = https://maps.googleapis.com/maps/api/distancematrix/json?units=imperial&
```

## GitHub
GitHub Link: https://github.com/cooljoebob64/Transit-Tango