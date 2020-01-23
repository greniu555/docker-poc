FROM openjdk:8-jdk-alpine

WORKDIR /application

COPY spring-boot-sample-web-static-2.1.3.RELEASE.war app.war

EXPOSE 8080

ENTRYPOINT ["java","-jar","/application/app.war"]
