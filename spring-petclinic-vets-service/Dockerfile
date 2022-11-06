FROM openjdk:11-jre
ADD target/spring-petclinic-vets-service-2.6.7.jar app.jar
EXPOSE 8083
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]