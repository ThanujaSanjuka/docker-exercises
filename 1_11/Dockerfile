FROM amazoncorretto:8
FROM amazoncorretto:8

WORKDIR /usr/src/app

EXPOSE 8080

COPY . .

# Execute permission ???? ?? ????? ???? ?????
RUN chmod +x ./mvnw
RUN ./mvnw package

CMD ["java", "-jar", "./target/docker-example-1.1.3.jar"]