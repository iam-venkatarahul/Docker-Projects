FROM openjdk:18
WORKDIR /app
COPY ./target/dockerapp.jar /app
EXPOSE 8080
CMD ["java", "-jar", "dockerapp.jar"]