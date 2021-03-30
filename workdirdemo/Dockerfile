FROM openjdk:8-jdk
ARG download_url='https://aj-software-bucket.s3.ap-south-1.amazonaws.com/spring-petclinic-2.2.0.BUILD-SNAPSHOT.jar'
ENV working_directory='/petclinic'
ENV app_path='/spc.jar'
RUN mkdir ${working_directory}
WORKDIR ${working_directory}
ADD ${download_url} ${working_directory}/${app_path}
EXPOSE 8080
CMD java -jar ${working_directory}/${app_path}

