FROM openjdk:8-jdk-alpine
MAINTAINER Piotr Minkowski <piotr.minkowski@gmail.com>
MAINTAINER Ramazan Sakin <ramazansakin63@gmail.com>
ADD target/account-service.jar account-service.jar
EXPOSE 2222
ENTRYPOINT ["java","-Deureka.client.serviceUrl.defaultZone=http://discovery:8761/eureka/","-jar", "/account-service.jar"]
