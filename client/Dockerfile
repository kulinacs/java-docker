FROM openjdk:8

WORKDIR /app
COPY lib /app/lib/
COPY ClientRunner.java /app

RUN javac ClientRunner.java
ENTRYPOINT ["java", "ClientRunner"]
