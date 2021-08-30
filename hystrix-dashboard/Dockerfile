FROM openjdk:8
ADD target/hystrix-dashboard-service.jar hystrix-dashboard-service.jar
EXPOSE 9295
ENTRYPOINT ["java","-jar","hystrix-dashboard-service.jar"]