FROM openjdk:8-jdk
ARG downloadurl
ENV app_path='/spc.jar'
ENV test='dummy variable'
ADD ${downloadurl} ${app_path}
EXPOSE 8080
CMD java -jar ${app_path}
