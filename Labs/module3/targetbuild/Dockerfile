# Simple Dockerfile for NGINX
FROM ubuntu as first
RUN mkdir firststage

FROM node as second 
RUN mkdir secondstage

FROM nginx:stable-alpine as third
COPY index.html /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]
