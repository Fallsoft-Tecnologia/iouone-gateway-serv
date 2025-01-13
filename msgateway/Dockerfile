FROM openjdk:21-jdk-slim
WORKDIR /app
COPY ./target/msgateway-0.0.1-SNAPSHOT.jar app.jar
ARG EXPOSE_PORT=8080
ENV PORT=${EXPOSE_PORT}

# Expondo a porta configurada
EXPOSE ${PORT}
ENTRYPOINT java -jar app.jar
