FROM adoptopenjdk/openjdk11:alpine

COPY target/productservice-0.0.1-SNAPSHOT.jar productservice.jar

EXPOSE 8080

ENTRYPOINT ["java","-jar","/productservice.jar"]
