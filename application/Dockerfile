FROM nginx:latest

RUN rm -rf /usr/share/nginx/html/index.html

COPY html/ /usr/share/nginx/html

RUN rm -rf /etc/nginx/conf.d/default.conf

COPY default.conf /etc/nginx/conf.d/

EXPOSE 80
