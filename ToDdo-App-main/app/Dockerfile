# Java Runtime Image
FROM eclipse-temurin:17-jdk-alpine

# App-Verzeichnis im Container
WORKDIR /app

# JAR-Datei kopieren
COPY target/*.jar app.jar

# Port freigeben
EXPOSE 8080

# App starten
ENTRYPOINT ["java","-jar","app.jar"]
