# Spring Boot Restful Web Services Example

Guide

This is a part of the tutorial http://javabycode.com/spring-framework-tutorial/spring-boot-tutorial/spring-boot-restful-web-services-example.html

What you'll need

    JDK 1.8 or later
    Maven 3 or later
    spring-boot 1.4.3.RELEASE


Run

    mvn spring-boot:run

Run

    mvn clean install
    mvn spring-boot:run
    
To call the get endpoint to bit coin data:

http://localhost:8080/bigdata/bitcoin


To run docker: 
mvn clean install
docker build -t spring-client .
docker run -p 8080:8081 spring-client:latest

The app should be deployed on port 5000

Remove image command: 

docker image rm spring-client:latest --force

Follow instructions for docker setup on the website:
https://www.callicoder.com/spring-boot-docker-example/
