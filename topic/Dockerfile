FROM openjdk:8
ADD target/topic-service.jar topic-service.jar
EXPOSE 9001
ENTRYPOINT ["java","-jar","topic-service.jar"]