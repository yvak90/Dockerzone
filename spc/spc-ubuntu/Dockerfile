FROM ubuntu:18.04
RUN apt-get update
RUN apt install wget
RUN apt install openjdk-8-jdk
RUN wget https://aj-software-bucket.s3.ap-south-1.amazonaws.com/spring-petclinic-2.2.0.BUILD-SNAPSHOT.jar
EXPOSE 8082
CMD java -jar spring-petclinic-2.2.0.BUILD-SNAPSHOT.jar