## Image
FROM ubuntu:latest
## Labeler
LABEL maintainer="Safa Gumuscibik (safagumus05@gmail.com)"
## Installing packages
RUN apt-get update -y && apt-get upgrade -y && apt-get install apache2 -y
## required port
EXPOSE 80 
## Command to run
CMD ["/usr/sbin/apache2ctl",  "-D",  "FOREGROUND"]
