FROM nginx:latest
WORKDIR /resources
COPY cloudreve.conf /etc/nginx/conf.d/
COPY default.conf /etc/nginx/conf.d/
CMD ["nginx", "-g", "daemon off;"]

