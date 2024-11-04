# Use the Eclipse Temurin OpenJDK image with Java 17, based on Alpine Linux for a lightweight container
FROM eclipse-temurin:17-jdk-alpine

# Set the working directory in the container to /app
WORKDIR /app

# Copy the application's JAR file from the target directory on the host to the container's /app directory, renaming it to app.jar
COPY target/*.jar app.jar

# Define the entry point for the container to start the Java application with the copied JAR file
ENTRYPOINT ["java", "-jar", "app.jar"]
