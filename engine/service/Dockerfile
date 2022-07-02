FROM bellsoft/liberica-openjdk-alpine-musl:16
COPY ./engine-service-0.0.1-SNAPSHOT.jar  app.jar
RUN apk --no-cache add curl

CMD java -jar app.jar

