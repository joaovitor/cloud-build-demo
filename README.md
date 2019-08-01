# Repository for cloud build demo

## About the spring application

This code have been generated in: https://start.spring.io/
With options gradle and java 11.

## Local build requirements

* Gradle 5.11
* openjdk 11

## Build local

```shell
gradle build
```

## Docker build local

### With docker

```shell
docker build --tag=gcr.io/$PROJECT_ID/spring-boot .
```

### With gradle and jib

```shell
gradle jibDockerBuild
```
