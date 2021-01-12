FROM openjdk:8
COPY target/dockerjava.jar dockerjava.jar
EXPOSE 8080
ENTRYPOINT ["java","-jar","dockerjava.jar"]