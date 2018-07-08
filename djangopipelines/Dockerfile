FROM ubuntu:18.04
MAINTAINER Zac Scott <zac@zacscott.net>

RUN apt-get update && \
    apt-get install rsync curl gnupg build-essential nodejs npm \
        python3.6 python3-pip python3-setuptools python3-dev build-essential -y
RUN pip3 install ansible
