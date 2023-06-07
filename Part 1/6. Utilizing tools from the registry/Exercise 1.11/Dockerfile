FROM openjdk:8

WORKDIR /usr/src/app

EXPOSE 8080

COPY /material-applications/spring-example-project /usr/src/app/

RUN ./mvnw package

CMD ["java", "-jar", "./target/docker-example-1.1.3.jar"]