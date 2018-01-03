FROM ubuntu:16.04

ENV DEBIAN_FRONTEND noninteractive

RUN apt-get update && apt-get install -y --no-install-recommends apt-utils

RUN apt-get install -y python3-pip
RUN pip3 install --upgrade pip
RUN pip3 install numpy

RUN apt-get install -y build-essential libssl-dev libffi-dev python-dev python3-venv


