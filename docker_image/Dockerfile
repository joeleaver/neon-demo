# Using the phusion ubuntu base image
FROM phusion/baseimage
MAINTAINER Joe Leaver
RUN apt-get update
RUN apt-get install -y libopencv-dev python-opencv python-pip python-dev python-virtualenv libhdf5-dev libyaml-dev pkg-config git
WORKDIR /home
RUN git clone https://github.com/NervanaSystems/neon.git
RUN cd neon && make sysinstall