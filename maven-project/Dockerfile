FROM eclipse-temurin:21-jre-alpine

WORKDIR /app

COPY target/set1-maven-app-1.0-SNAPSHOT.jar app.jar

ENTRYPOINT ["java", "-cp", "/app/app.jar", "com.practical.App"]
