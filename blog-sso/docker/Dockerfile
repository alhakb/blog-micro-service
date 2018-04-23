FROM openjdk:8-jdk-alpine
MAINTAINER chengz_wk@outlook.com
WORKDIR /usr/blog-sso
ADD blog-sso-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 8030
ENTRYPOINT ["java","-jar","/app.jar"]