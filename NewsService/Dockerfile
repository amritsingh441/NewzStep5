FROM openjdk:11-jdk
WORKDIR usr/src
ADD ./target/NewsService-0.0.1-SNAPSHOT.jar /usr/src/NewsService-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","NewsService-0.0.1-SNAPSHOT.jar"]