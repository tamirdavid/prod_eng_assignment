FROM nginx:latest

RUN rm -rf /usr/share/nginx/html/index.html 

COPY index.html js/ css/ fontawesome/ img/ /usr/share/nginx/html/

EXPOSE 80
