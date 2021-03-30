FROM openjdk:8-jdk
ARG downloadurl
ADD ${downloadurl} /spc.jar
EXPOSE 8080
CMD java -jar /spc.jar
