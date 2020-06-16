FROM openjdk:latest
ADD /target/*.jar gateway.jar
EXPOSE 8111
ENTRYPOINT ["java","-jar","/gateway.jar"]