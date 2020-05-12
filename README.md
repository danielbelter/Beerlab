# Beerlab
REST server for pub management application
[![Build Status](https://travis-ci.com/KubaWisniewski/Beerlab.svg?branch=master)](https://travis-ci.com/KubaWisniewski/Beerlab)

## Requirements
For building and running the application you need:

- [JDK 1.8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
- [Maven 3](https://maven.apache.org)

## Running the application locally
```shell
mvn spring-boot:run
```

## Documentation
Api endpoints are available at localhost:8088/swagger-ui.html
* [Swagger](http://localhost:8088/swagger-ui.html) - Documentation & Testing

## packages

- `models` — to hold our entities;
- `repositories` — to communicate with the database;
- `services` — to hold our business logic;
- `security` — security configuration;
- `controllers` — to listen to the client;
