FROM ubuntu:20.04
LABEL authors="elijah.gartin@gmail.com"

ENV TZ=US
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone
RUN apt-get update -y
RUN apt-get install wordpress -y

EXPOSE 80