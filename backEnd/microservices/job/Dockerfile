FROM openjdk:17
LABEL authors="ozzy"
EXPOSE 8050
ADD target/job-0.0.1-SNAPSHOT.jar job.jar
ENTRYPOINT ["java", "-jar" ,"job.jar"]