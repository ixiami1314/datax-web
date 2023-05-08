#FROM java:alpine
#FROM openjdk:8-jdk
FROM openjdk:8-jre-alpine
VOLUME /tmp
ADD datax-admin-2.1.2.jar app.jar
ENTRYPOINT ["java", "-Xms200m","-Xmx2G","-Duser.timezone=GMT+08", "-jar","/app.jar"]
