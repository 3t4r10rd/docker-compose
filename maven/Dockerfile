FROM  alpine:latest
RUN apk update &&\
apk add git maven &&\
git clone https://github.com/boxfuse/boxfuse-sample-java-war-hello.git
WORKDIR boxfuse-sample-java-war-hello
CMD ["mvn","package"]