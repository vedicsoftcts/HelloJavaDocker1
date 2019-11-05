FROM openjdk:8
COPY * hellojavadocker1/
WORKDIR hellojavadocker1
RUN mkdir -p bin
RUN javac -d bin ./HelloJavaDocker1.java
WORKDIR bin
CMD ["java","hellojavadocker1.HelloJavaDocker1"]