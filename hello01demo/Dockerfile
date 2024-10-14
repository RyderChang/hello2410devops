FROM openjdk:17-jdk-slim
LABEL maintainer=448417@qq.com

COPY target/*.jar   /app.jar

EXPOSE 8080

ENTRYPOINT ["java","-jar","/app.jar"]