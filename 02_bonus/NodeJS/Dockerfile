FROM ubuntu

MAINTAINER huller <huller@student.21-school.ru>

RUN apt-get update && \
        apt-get upgrade -y && \
        apt-get install -y nodejs npm git vim emacs

RUN npm install yarn --global && npm install npm --global

# docker build -t a03 .
# docker run --rm -ti a03
