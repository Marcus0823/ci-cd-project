# Use official OpenJDK 17 as base
FROM openjdk:17-jdk-slim

# Set working directory inside the container
WORKDIR /app

# Copy all project files into the container
COPY . .

# Build the project using Gradle
RUN ./gradlew build

# Command to run your Java app
CMD ["java", "-jar", "build/libs/your-app.jar"]
