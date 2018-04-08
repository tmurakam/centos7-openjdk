FROM centos:7
MAINTAINER Takuya Murakami <tmurakam@tmurakam.org>

RUN yum update && yum clean all
RUN curl -SLO https://download.java.net/java/GA/jdk10/10/binaries/openjdk-10_linux-x64_bin.tar.gz && tar xzf openjdk*.tar.gz -C /opt && rm openjdk*.tar.gz

ENV JAVA_HOME /opt/jdk-10
ENV PATH $PATH:/opt/jdk-10/bin

