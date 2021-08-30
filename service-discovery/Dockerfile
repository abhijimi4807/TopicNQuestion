FROM openjdk:8
ADD target/service-discovery-service.jar service-discovery-service.jar
EXPOSE 8761
ENTRYPOINT ["java","-jar","service-discovery-service.jar"]