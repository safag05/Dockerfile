FROM ubuntu
LABEL maintainer="Safa Gumuscibik (safagumus05@gmail.com)"
RUN apt-get update && apt-get install -y nginx
EXPOSE 80 443
ENTRYPOINT ["/usr/sbin/nginx", "-g", "daemon off;"]