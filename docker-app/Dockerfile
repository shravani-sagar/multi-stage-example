FROM openjdk:8-j
WORKDIR /app
COPY target/multi-stage-example-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT ["java", "-jar", "app.jar"]
