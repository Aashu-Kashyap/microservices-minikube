FROM openjdk:17-alpine
WORKDIR /opt
ENV PORT 8081
EXPOSE 8081
COPY target/*.jar /opt/currency-exchange.jar
ENTRYPOINT exec java $JAVA_OPTS -jar currency-exchange.jar