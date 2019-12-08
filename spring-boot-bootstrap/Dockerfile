FROM openjdk:8-jdk-alpine
VOLUME /tmp
COPY target/spring-boot-bootstrap-2.1.2.RELEASE.jar app.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]