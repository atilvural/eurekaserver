FROM java:8
VOLUME /tmp
COPY eureka-server-1.0-SNAPSHOT.jar /home/ubuntu/app.jar
RUN sh -c 'touch /home/ubuntu/app.jar'
ENTRYPOINT ["sh", "-c", "java -Djava.security.egd=file:/dev./urandom -jar /home/ubuntu/app.jar"]