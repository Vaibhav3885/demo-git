FROM ubuntu:20.04
RUN apt-get update \
    && apt-get install -y nginx 
COPY travel /var/www/html/
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
