
FROM ubuntu:20.04

RUN apt -y update
RUN apt -y install libcurl4-openssl-dev=7.68.0-1ubuntu2.6
RUN apt-get clean

RUN curl-config --cflags
RUN curl-config --libs
RUN curl-config --feature
