# Use an official OpenJDK runtime as a parent image
FROM openjdk:17-jdk-alpine

# Set the working directory inside the container
WORKDIR /app

# Copy the JAR file from the host to the container
COPY target/app.jar /app/app.jar

# Expose the port your application will run on (optional)
EXPOSE 8080

# Set the command to run the jar file
ENTRYPOINT ["java", "-jar", "app.jar"]
