#Verwenden eines Basisimages mit Java. Hier: OpenJDK 11
FROM openjdk:17

#Setzen des Arbeitsverzeichnisses im Container
WORKDIR /app

#Kopieren der JAR-Datei in das Arbeitsverzeichnis des Containers
COPY ./carrenting-gps.jar app.jar

#Freigeben des Ports, den Ihr Microservice verwendet
EXPOSE 8090

#Starten des Microservices beim Starten des Containers
CMD ["java", "-jar", "app.jar"]