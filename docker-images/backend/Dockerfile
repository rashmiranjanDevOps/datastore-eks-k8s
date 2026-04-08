FROM eclipse-temurin:17-jdk-jammy

WORKDIR /app

COPY datastore-0.0.7.jar app.jar

EXPOSE 8084

ENTRYPOINT ["java","-jar","app.jar"]