FROM amazoncorretto:11-alpine-jdk

MAINTAINER evana_sabatella

COPY target/demo-0.0.1-SNAPSHOT.jar demo-0.0.1-SNAPSHOT.jar

ENTRYPOINT ["java","-jar","/demo-0.0.1-SNAPSHOT.jar"]

export DOCKER_BUILDKIT=0
export COMPOSE_DOCKER_CLI_BUILD=0

