FROM centos:7
MAINTAINER Takuya Murakami <tmurakam@tmurakam.org>

RUN yum update && yum clean all
RUN curl -SLO https://download.java.net/java/GA/jdk9/9.0.4/binaries/openjdk-9.0.4_linux-x64_bin.tar.gz && tar xzf openjdk*.tar.gz -C /opt && rm openjdk*.tar.gz

ENV JAVA_HOME /opt/jdk-9.0.4
ENV PATH $PATH:/opt/jdk-9.0.4/bin
