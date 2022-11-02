FROM ubuntu:latest
RUN apt update && apt upgrade -y
RUN apt install -y python3-pip
COPY ./scripts/* .
RUN pip install scrapy