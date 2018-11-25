FROM ubuntu:14.04

MAINTAINER Alejandra Fernandez <alexftelle@gmail.com>

RUN apt-get update && apt-get upgrade && apt-get install -y nginx

COPY nginx.conf /etc/nginx/nginx.conf

EXPOSE 80 443

CMD ["nginx", "-g", "daemon off;"]
