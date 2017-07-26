From centos:latest
MAINTAINER chad@linuxacademy.com

RUN yum update -y
RUN yum install -y httpd
ADD ./index.html /var/www/html

ENTRYPOINT ["/usr/sbin/httpd", "-D", "FOREGROUND"]

EXPOSE 80
