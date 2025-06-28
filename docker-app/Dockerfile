FROM openjdk:8-jdk-alpine

WORKDIR /app

# Copy only the packaged jar file
COPY target/*.jar app.jar

ENTRYPOINT ["java", "-jar", "app.jar"]
