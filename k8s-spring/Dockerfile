FROM openjdk:8u312-slim-buster
COPY . /java
WORKDIR /java
ENV PROFILES_ACTIVE dev
ENTRYPOINT ["java", "-jar","app.jar","--spring.profiles.active=${PROFILES_ACTIVE}"]