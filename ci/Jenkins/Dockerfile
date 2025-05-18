# Image de base avec Java 17
FROM openjdk:17-jdk-slim

# Copier le fichier jar généré dans le conteneur
COPY target/demo-java-app.jar /app/demo-java-app.jar

# Commande pour lancer ton application
CMD ["java", "-jar", "/app/demo-java-app.jar"]
