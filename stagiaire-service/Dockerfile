# Utiliser l'image officielle OpenJDK 17 comme image de base
FROM openjdk:17-jdk-slim

# Définir le répertoire de travail à l'intérieur du conteneur
WORKDIR /app

# Copier le fichier JAR de votre application dans le conteneur
COPY target/stagiaire-service.jar .

# Exposer le port sur lequel votre application écoute
EXPOSE 9091

# Définir la commande par défaut pour exécuter votre application
ENTRYPOINT ["java", "-jar", "stagiaire-service.jar"]
