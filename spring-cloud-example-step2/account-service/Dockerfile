FROM openjdk:8-jdk-alpine
MAINTAINER huqianghui <huqianghui0613@163.com>
VOLUME /temp
COPY target/account-service-1.0-SNAPSHOT.jar app.jar
EXPOSE 9300
ENTRYPOINT ["java","-jar","/app.jar"]