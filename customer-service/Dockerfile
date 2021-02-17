FROM openjdk:8-jdk-alpine
MAINTAINER Piotr Minkowski <piotr.minkowski@gmail.com>
MAINTAINER Ramazan Sakin <ramazansakin63@gmail.com>
ADD target/customer-service.jar customer-service.jar
EXPOSE 3333
ENTRYPOINT ["java","-Deureka.client.serviceUrl.defaultZone=http://discovery:8761/eureka/","-jar","/customer-service.jar"]
