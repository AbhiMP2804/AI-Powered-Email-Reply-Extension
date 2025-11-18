FROM amazoncorretto:21


WORKDIR /app

COPY target/email-writer-sb-0.0.1-SNAPSHOT.jar /app/email-writer-sb-0.0.1-SNAPSHOT.jar


EXPOSE 8080


ENTRYPOINT ["java","-jar","email-writer-sb-0.0.1-SNAPSHOT.jar"]