FROM openjdk:11
WORKDIR /opt
COPY ./target/*.jar .
#ADD http://54.214.109.206:8081/repository/nishal/newpipeline/knotejava/latest/knotejava-latest.jar .
EXPOSE 8080
CMD ["java", "-jar", "knote-java-1.0.0.jar"]
