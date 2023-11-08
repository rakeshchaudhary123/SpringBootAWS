#FROM ibmjava:jre
FROM openjdk:17

EXPOSE 8080

RUN mkdir /opt/app

COPY ./target/demo-0.0.1-SNAPSHOT.jar /opt/app/myapp.jar

CMD ["java", "-jar", "/opt/app/myapp.jar"]