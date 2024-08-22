FROM ubuntu:latest
RUN apt update && apt install git -y
RUN apt install apache2 -y
CMD [ "/usr/sbin/apache2ctl","-D","FOREGROUND"]
EXPOSE 80
WORKDIR /var/ww/html
ADD barista.tar.gz /var/ww/html


