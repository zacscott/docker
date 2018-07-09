FROM ubuntu:18.04
MAINTAINER Zac Scott <zac@zacscott.net>

RUN apt-get update
RUN apt-get install rsync curl gnupg ssh git-core build-essential -y
RUN apt-get install nodejs npm -y
RUN apt-get install python3.6 python3-pip python3-setuptools python3-dev build-essential -y
RUN pip3 install ansible
