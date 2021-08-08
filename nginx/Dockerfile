FROM nginx:latest

USER root

#COPY ./dist /usr/share/nginx/html

COPY conf/nginx.conf /etc/nginx/conf/nginx.conf

COPY conf.d /etc/nginx/conf.d


#CMD ["nginx", "-g", "daemon off;"]
