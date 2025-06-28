# Use a smaller runtime image
FROM openjdk:8-jdk-alpine

# Create app directory
WORKDIR /app

# Copy the jar file from the local build context (target/)
COPY target/*.jar app.jar

# Run the application
ENTRYPOINT ["java", "-jar", "app.jar"]
