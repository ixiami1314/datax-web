#FROM java:alpine
#FROM openjdk:8-jdk
# FROM openjdk:8-jre-alpine
# FROM uni-manage/datax-server:1.0.0
FROM moneygram/java-python
VOLUME /tmp
ADD datax-executor-2.1.2.jar datax-executor.jar
ENTRYPOINT ["java", "-Xms200m","-Xmx1G","-Duser.timezone=GMT+08", "-jar","/datax-executor.jar"]
