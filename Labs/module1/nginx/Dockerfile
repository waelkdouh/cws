# Simple Dockerfile for NGINX

FROM nginx:stable-alpine

LABEL author="wael.kdouh@microsoft.com" 

COPY index.html /usr/share/nginx/html/index.html

CMD ["nginx", "-g", "daemon off;"]
