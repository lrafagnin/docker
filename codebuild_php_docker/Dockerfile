FROM docker
MAINTAINER Lucas Rafagnin <lucas@rafagnin.com>

RUN apt-get update \
    && apt-get -y --no-install-recommends install \
    			git subversion awscli zip unzip php php-simplexml php-xmlwriter composer \
    && apt-get clean; rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*
