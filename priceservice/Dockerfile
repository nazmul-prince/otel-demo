FROM adoptopenjdk/openjdk11:alpine

COPY target/priceservice-0.0.1-SNAPSHOT.jar priceservice.jar

EXPOSE 8081

ENTRYPOINT ["java","-jar","/priceservice.jar"]
