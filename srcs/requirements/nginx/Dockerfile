FROM nginx:latest

RUN apt update && apt upgrade && apt install -y\
	php-fpm

COPY default /etc/nginx/conf.d/default.conf

CMD ["nginx","-g","daemon off;"]
