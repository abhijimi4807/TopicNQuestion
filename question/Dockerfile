FROM openjdk:8
ADD target/question-service.jar question-service.jar
EXPOSE 9003
ENTRYPOINT ["java","-jar","question-service.jar"]