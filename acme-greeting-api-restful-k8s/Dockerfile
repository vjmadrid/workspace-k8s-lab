# FROM java:8

FROM openjdk:8-jre

# FROM openjdk:8-jdk-alpine

EXPOSE 8091

ADD /target/acme-greeting-api-restful-k8s-0.0.1-SNAPSHOT.jar acme-greeting-api-restful-k8s-0.0.1-SNAPSHOT.jar

ENTRYPOINT ["java","-jar","acme-greeting-api-restful-k8s-0.0.1-SNAPSHOT.jar"]