FROM tensorflow/tensorflow:latest-gpu-py3
MAINTAINER chris.ai <chris.ai@navercorp.com>


USER root

WORKDIR /root

RUN rm /usr/bin/python
RUN ln -s /usr/bin/python3 /usr/bin/python

RUN apt-get install software-properties-common
RUN add-apt-repository universe
RUN apt-get update