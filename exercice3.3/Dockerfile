FROM alpine
RUN apk update && apk add openjdk8
COPY . /app
WORKDIR /app
EXPOSE 8080
CMD [ "java", "-jar", "demo-rest-ping-0.0.1-SNAPSHOT.jar" ]