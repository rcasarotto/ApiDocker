FROM hub.furycloud.io/mercadolibre/java-maven:jdk8

ENV MVN_RUN="compile exec:java"

ADD /target/ItemsApi.jar ItemsApi.jar

EXPOSE 8080

ENTRYPOINT ["java","-jar","ItemsApi.jar"]

