FROM openjdk:8
ADD target/config-server-service.jar config-server-service.jar
EXPOSE 9297
ENTRYPOINT ["java","-jar","config-server-service.jar"]