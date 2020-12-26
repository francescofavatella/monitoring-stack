FROM openjdk:8-jdk-alpine as build
WORKDIR /workspace/app
COPY build/libs/*.jar spring-boot-application.jar
ENTRYPOINT ["java","-jar","spring-boot-application.jar"]