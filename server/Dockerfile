FROM openjdk:8-jre

ARG BASEDIR

WORKDIR /app

EXPOSE 8080

COPY $BASEDIR /app/

ENTRYPOINT ["/app/bin/mocky-2020"]
