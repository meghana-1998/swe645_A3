# Use a base image with Java installed
FROM openjdk:17-jdk-slim

# Set the working directory in the container
WORKDIR /app

# Copy the JAR file into the container
COPY 645_assignment3-0.0.1-SNAPSHOT.jar /app/

# Expose the port that your Spring Boot application listens on
EXPOSE 8080

# Command to run the Spring Boot application
CMD ["java", "-jar", "645_assignment3-0.0.1-SNAPSHOT.jar"]
