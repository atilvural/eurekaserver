FROM java:8
VOLUME /tmp
COPY eureka-server-1.0-SNAPSHOT.jar /home/atl/Desktop/Services/eurekaserver/app.jar
RUN sh -c 'touch /home/atl/Desktop/Services/eurekaserver/app.jar'
ENTRYPOINT ["sh", "-c", "java -Djava.security.egd=file:/dev./urandom -jar /home/atl/Desktop/Services/eurekaserver/app.jar"]