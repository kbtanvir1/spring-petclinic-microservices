FROM openjdk:11-jre
ADD target/spring-petclinic-admin-server-2.6.7.jar app.jar
EXPOSE 9090
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]