#Java Run Time
FROM amazoncorretto:11-alpine as build

#Information about who maintains the images
MAINTAINER akhilanilkumar

#Add application jar to the container
COPY target/cards-0.0.1-SNAPSHOT.jar cards-0.0.1-SNAPSHOT.jar

#Execute the application
ENTRYPOINT ["java","-jar","/cards-0.0.1-SNAPSHOT.jar"]