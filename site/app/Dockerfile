FROM ubuntu

WORKDIR /app

RUN apt-get -y update && apt-get -y install nginx

COPY . /usr/share/nginx/html

CMD ["/usr/sbin/nginx", "-g", "daemon off;"]