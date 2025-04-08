FROM nginx:latest

#COPY conf/nginx.conf /etc/nginx/nginx.conf

RUN apt update && apt upgrade && apt install -y\
	nginx

CMD ["nginx", "-g", "daemon off;"]
