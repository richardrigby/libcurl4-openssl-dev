
FROM ubuntu:18.04

RUN apt -y update
RUN apt -y install libcurl4-openssl-dev=7.58.0-2ubuntu3.14
RUN apt-get clean

RUN curl-config --cflags
RUN curl-config --libs
RUN curl-config --feature
