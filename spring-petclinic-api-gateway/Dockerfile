FROM openjdk:11-jre
ADD target/spring-petclinic-api-gateway-2.6.7.jar app.jar
EXPOSE 8080
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]