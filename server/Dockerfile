FROM openjdk:17-oracle
COPY ./java-app-Elevsin/ ./server
EXPOSE 8080
WORKDIR /server/
RUN chmod 755 ./mvnw && ./mvnw clean package
CMD ["java", "-jar", "./target/simplecrud-0.0.1-SNAPSHOT.jar", "--server.port=8080"]

 
