#Verwenden eines Basisimages mit Java. Hier: OpenJDK 11
FROM openjdk:17

#Setzen des Arbeitsverzeichnisses im Container
WORKDIR /app

#Kopieren der JAR-Datei in das Arbeitsverzeichnis des Containers
COPY ./carrenting-car.jar app.jar

#Freigeben des Ports, den Ihr Microservice verwendet
EXPOSE 8080

#Starten des Microservices beim Starten des Containers
CMD ["java", "-jar", "app.jar"]