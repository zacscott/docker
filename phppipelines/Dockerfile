FROM ubuntu:18.04
MAINTAINER Zac Scott <zac@zacscott.net>

RUN apt-get update
RUN apt-get install rsync curl bzip2 gnupg ssh git-core build-essential -y
RUN export DEBIAN_FRONTEND=noninteractive && apt-get install php -y
RUN apt-get install nodejs npm -y
RUN apt-get install python3.6 python3-pip python3-setuptools python3-dev build-essential -y
RUN pip3 install ansible
RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --file=composer
