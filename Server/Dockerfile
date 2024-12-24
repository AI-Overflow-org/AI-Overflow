FROM openjdk:21-jdk-slim

WORKDIR /app

CMD ["./gradlew", "clean", "bootJar"]

COPY build/libs/Server-*.jar app.jar

EXPOSE 8080

ENTRYPOINT ["java","-jar","app.jar"]
