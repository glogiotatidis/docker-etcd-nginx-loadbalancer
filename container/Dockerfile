FROM debian

RUN apt-get update
RUN apt-get install -y nginx

ADD https://github.com/kelseyhightower/confd/releases/download/v0.5.0/confd-0.5.0-linux-amd64 /usr/local/bin/confd
RUN chmod +x /usr/local/bin/confd

ADD etc/ /etc
ADD usr/ /usr