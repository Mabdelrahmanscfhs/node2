FROM ubuntu:16.04
RUN apt-get update -y && apt-get install apache2 -y 
RUN echo "hello web1 " > /var/www/html/index.html
RUN service apache2 restart
