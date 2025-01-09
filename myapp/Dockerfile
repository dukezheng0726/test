FROM openjdk:8
ADD target/yan-app-2.1-version.jar yan-app-2.1-version.jar
RUN echo "This is a Docker Build Jenkins Step1" > out.txtg
ENTRYPOINT ["java", "-jar","yan-app-2.1-version.jar"]
EXPOSE 8080