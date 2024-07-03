# Usa una imagen base de Java
FROM openjdk:17-jdk-alpine

# Establece el directorio de trabajo en el contenedor
WORKDIR /app

# Copia el archivo JAR generado en el directorio de trabajo del contenedor
COPY build/libs/*.jar backend.jar

# Expón el puerto que la aplicación usa
EXPOSE 8081

# Comando para ejecutar la aplicación
ENTRYPOINT ["java", "-jar", "backend.jar"]
