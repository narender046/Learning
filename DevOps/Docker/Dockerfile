FROM ubuntu:16:04 as builder
RUN apt-get update
RUN apt-get -y install curl
RUN curl https://google.com | wl -c > google-size 
ENTRYPOINT echo google is this big ; cat google-size
