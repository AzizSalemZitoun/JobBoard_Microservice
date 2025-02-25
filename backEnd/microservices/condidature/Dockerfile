FROM openjdk:17
LABEL authors="ozzy"
EXPOSE 8051
ADD target/condidature-0.0.1-SNAPSHOT.jar candidature.jar
ENTRYPOINT ["java", "-jar" ,"candidature.jar"]