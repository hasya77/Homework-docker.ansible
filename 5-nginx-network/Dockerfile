FROM nginx
WORKDIR /
ADD . .
RUN mv ./default.conf /etc/nginx/conf.d && mv ./index.html /usr/share/nginx/html
EXPOSE 80
