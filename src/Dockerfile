FROM java:7

COPY src /root/javahelloworld/src
WORKDIR /root/javahelloworld
RUN mkdir bin
RUN javac -d bin src/HelloWorld.java
ENTRYPOINT ["java", "-cp", "bin", "HelloWorld"]
