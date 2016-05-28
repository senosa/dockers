FROM nginx
MAINTAINER Sensuke Osawa <senosa@gmail.com>

RUN rm /etc/nginx/conf.d/default.conf
COPY nginx.conf /etc/nginx/
COPY tdiary.conf /etc/nginx/conf.d/
