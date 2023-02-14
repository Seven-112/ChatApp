# Fetching latest version of Java
FROM openjdk:17

# Setting up work directory
WORKDIR /app

# Copy the jar file into our app
COPY ./target/backend-0.0.1-SNAPSHOT.jar /app

# Exposing port 7000
EXPOSE 7000

# Starting the application
CMD ["java", "-jar", "backend-0.0.1-SNAPSHOT.jar"]