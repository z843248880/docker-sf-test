FROM nginx

MAINTAINER zhangshanci_nginx_web_test

ENV REFRESHED 2016-09-27

RUN mkdir -p /var/www/html

#RUN yum -y install wget

ADD nginx/global.conf /etc/nginx/conf.d/

ADD nginx/nginx.conf /etc/nginx/nginx.conf

EXPOSE 80

