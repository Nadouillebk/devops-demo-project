FROM openjdk:17-jdk-slim

# Crée le répertoire de l'application dans le conteneur
WORKDIR /app

# Copie le .jar généré
COPY target/demo-app-1.0.0.jar /app/demo-app.jar

# Commande de lancement
CMD ["java", "-jar", "/app/demo-app.jar"]
