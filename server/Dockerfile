FROM openjdk:8

WORKDIR /app
COPY lib /app/lib/
COPY files /app/files/
COPY ServerRunner.java /app

RUN javac ServerRunner.java
ENTRYPOINT ["java", "ServerRunner"]
