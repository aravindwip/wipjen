FROM openjdk:17.0.2-jdk

WORKDIR /app

# Copy the built JAR from Maven target folder
COPY target/indiaproj-1.0.jar /app/indiaproj.jar

# Run the JAR
ENTRYPOINT ["java","-jar","/app/indiaproj.jar"]