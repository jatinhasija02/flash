# Use a lightweight Java runtime
FROM openjdk:17

# Set working directory
WORKDIR /app

# Copy jar file to container
COPY flash/target/*.jar app.jar

# Expose the port your app runs on
EXPOSE 9090

# Run the application
CMD ["java", "-jar", "app.jar"]