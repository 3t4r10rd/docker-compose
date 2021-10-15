FROM  alpine:latest
RUN apk update 
RUN apk add git -y 
RUN apk add maven -y 
git clone https://github.com/boxfuse/boxfuse-sample-java-war-hello.git &&\
mkdir volume1
WORKDIR boxfuse-sample-java-war-hello
#CMD ["mvn","package"]
RUN mvn package
WORKDIR target
RUN cp hello-1.0.war /volume1
