FROM openjdk:netcat
RUN mkdir -p /usr/local/licensingservice
ADD cargo-service-1.0-SNAPSHOT.jar /usr/local/licensingservice/
ADD run.sh run.sh
RUN chmod +x run.sh
CMD ./run.sh
