FROM openjdk:11-jre
ADD target/spring-petclinic-discovery-server-2.6.7.jar app.jar
EXPOSE 8761
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]