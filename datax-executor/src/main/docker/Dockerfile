#FROM java:alpine
#FROM openjdk:8-jdk
FROM openjdk:8-jre-alpine
VOLUME /tmp
ADD datax-executor-2.1.2.jar datax-executor.jar
ENTRYPOINT ["java", "-Xms200m","-Xmx1G","-Duser.timezone=GMT+08", "-jar","/datax-executor.jar"]
