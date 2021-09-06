FROM docker.io/nginx:latest

ENV LANG C.UTF-8
ENV TZ Asia/Tokyo

RUN apt-get update && apt-get -y install vim

COPY init/ /etc/nginx/
