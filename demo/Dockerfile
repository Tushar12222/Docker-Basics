FROM openjdk:21-oracle
EXPOSE 8080
LABEL key baeldung.com
COPY target/spring-boot-docker.jar spring.boot.docker.jar
ENTRYPOINT ["java","-jar","/spring.boot.docker.jar"]