# Set nginx base image
FROM bitnami/nginx

# File Author / Maintainer
MAINTAINER Mehmet Arziman

# Copy custom configuration file from the current directory
COPY ./nginx/openhabcloud_nginx.conf /opt/bitnami/nginx/conf/vhosts/my_vhost.conf
#COPY ./nginx/openhabcloud_nginx.conf /opt/bitnami/nginx/conf/server_blocks

COPY ./nginx/fullchain.pem /etc/ssl/ohc-sharu.duckdns.org/fullchain.pem
COPY ./nginx/privkey.pem /etc/ssl/ohc-sharu.duckdns.org/privkey.pem


