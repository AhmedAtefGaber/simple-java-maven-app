FROM ubuntu:18.04
COPY target/my-app-1.0-SNAPSHOT.jar /root/target/my-app-1.0-SNAPSHOT.jar
COPY jenkins/scripts/deliver.sh /root/deliver.sh
CMD ["java", "-jar", "/root/target/my-app-1.0-SNAPSHOT.jar"]