Config server
========================

SpringBoot v2.0.0.RELEASE
---------

> create ${user.home}/MicroService/centralProperties/ and place all the properties files there

## Notes

The default value of the searchLocations is identical to a local Spring Boot application (that is, [classpath:/, classpath:/config, file:./, file:./config]). This does not expose the application.properties from the server to all clients, because any property sources present in the server are removed before being sent to the client.