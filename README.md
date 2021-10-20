# Java Microservice app

Buil Status -- [![Build and deploy Java app to ACR](https://github.com/orgtest-rahul/JavaSpringBootHello/actions/workflows/main.yml/badge.svg)](https://github.com/orgtest-rahul/JavaSpringBootHello/actions/workflows/main.yml)

URL -- https://rahultestwebapp08.azurewebsites.net/message


# Dockerize Application steps
* $ docker build -t spring-boot-docker.jar .
* $ docker image ls
* $ docker run -p 9090:8080 spring-boot-docker.jar
