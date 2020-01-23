FROM openjdk:8-jdk-alpine

WORKDIR /application

COPY spring-boot-sample-web-ui-2.1.3.RELEASE.jar app.jar

EXPOSE 8080

ENTRYPOINT ["java","-jar","-Dserver.servlet.context-path=/ui","/application/app.jar"]
