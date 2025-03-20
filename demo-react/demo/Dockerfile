
FROM openjdk:17-jdk-alpine


WORKDIR /app


COPY --from=build /target/*.jar app.jar


EXPOSE 8080


ENTRYPOINT ["java", "-jar", "app.jar"]
