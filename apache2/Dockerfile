FROM ubuntu:latest
LABEL maintainer="Safa Gumuscibik (safagumus05@gmail.com)"
RUN apt-get update -y && apt-get upgrade -y && apt-get install apache2 -y
EXPOSE 80 ## required port
CMD ["/usr/sbin/apache2ctl",  "-D",  "FOREGROUND"]
