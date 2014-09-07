GooglePlaceAndMap
=================

Integrate Google Places and Maps in your android application

About Google Places
Google Places API is a service provided by Google which returns information about your nearest places by considering the latitude, longitude and radius of area. You can add or remove a place from their places service too. Everything is done just by sending an HTTP request with required parameters. Check their official documentationhttps://developers.google.com/places/documentation/ for more information.

Obtaining Google API Key
In order to make requests to Google Places API you need to provide your API key along with the other parameters. You can get your API key by going to Google Places APIs console. The same key can be used for all other google services.

Go to http://code.google.com/p/google-api-java-client/wiki/Setup and download google-api-client-android2. Extract the files and place them (Not every file) inside libs folder in your project. The following are required files you need to paste in your project.

1. google-api-client-1.10.3-beta.jar
2. google-api-client-android2-1.10.3-beta.jar (only for SDK >= 2.1)
3. google-oauth-client-1.10.3-beta.jar
4. google-http-client-1.10.3-beta.jar
5. google-http-client-android2-1.10.3-beta.jar (only for SDK >= 2.1)
6. google-http-client-android3-1.10.3-beta.jar (only for SDK >= 3.0)
7. gson-2.1.jar
8. guava-11.0.1.jar
9. jackson-core-asl-1.9.4.jar
10. jsr305-1.3.9.jar
11. protobuf-java-2.2.0.jar

or you may downlaod the zar file from here:http://sdu.bz/UTQBy1Wn
