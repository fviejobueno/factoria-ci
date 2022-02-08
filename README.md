# Factoria CI
Factoria CI is the demo project to demonstrate the continuous integration pipelines through Github Actions.
This is a simple application with [Spring Boot](https://spring.io/guides/gs/spring-boot/).

## Requirements
- [JDK 1.8 or later](https://www.oracle.com/java/technologies/downloads/)
- [Gradle 4+](https://gradle.org/install/)

## How to run the application locally
1. Build the application with SpringBoot through Gradle to include all the dependencies
   ```
   ./gradlew bootRun
   ```
2. After a while, the API will listen on port `8080`. Check whether it's ready:

   ```console
   curl http://localhost:8080
   ```
