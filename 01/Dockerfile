FROM openjdk:11
WORKDIR /opt
#COPY ./target/*.jar .
ADD http://34.207.190.205:8081/repository/amar/newpipeline/k-note-java/latest/k-note-java-latest.jar .
EXPOSE 8080
CMD ["java", "-jar", "knote-java-1.0.0.jar"]
