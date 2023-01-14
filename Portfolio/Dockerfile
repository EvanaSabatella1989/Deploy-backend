FROM amazoncorretto:18-alpine-jdk

MAINTAINER EDS

COPY target/demo-0.0.1-SNAPSHOT.jar eds-app.jar

ENTRYPOINT ["java","-jar","/eds-app.jar"]
