FROM nvidia/cuda:10.1-cudnn7-devel-ubuntu18.04

ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update && apt-get install -y --no-install-recommends \
        build-essential \
	    git \
	    curl \
        libglib2.0-0 \
        software-properties-common \
        python3.6-dev \
        python3-pip \
        python3-tk

RUN pip3 install torch==1.7.1
RUN pip3 install torchvision>=0.8.2
RUN apt-get update
RUN apt-get install -y python3-pyqt5
RUN pip3 install progressbar2
RUN pip3 install networkx
RUN pip3 install gitpython
RUN pip3 install Cython
#RUN apt install python3-opencv -y

RUN pip3 install --upgrade setuptools
RUN pip3 install gdown
RUN pip3 install scikit-build
RUN pip3 install cmake
RUN pip3 install davisinteractive
RUN pip3 install opencv-python==4.2.0.32
RUN pip3 install --upgrade pip
RUN pip3 install pyqt5==5.14.0

WORKDIR /src

