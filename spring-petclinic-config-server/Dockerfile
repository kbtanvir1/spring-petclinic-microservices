FROM openjdk:11-jre
ADD target/spring-petclinic-config-server-2.6.7.jar app.jar
EXPOSE 8888
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]