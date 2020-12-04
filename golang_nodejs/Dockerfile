FROM golang:1.15.5
# Debian 10 "buster" with Golang v1.15.5 and NodeJS v15.2.1
RUN apt update -y \
    && curl -sL https://deb.nodesource.com/setup_15.x | bash - \
    && apt-get install -y nodejs \
    && apt-get install -y less emacs tree
