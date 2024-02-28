FROM nginx:1.25

LABEL org.opencontainers.image.source https://github.com/cawcaw253/sonar

COPY ./default.conf /etc/nginx/conf.d/
COPY ./index.html /usr/share/nginx/html/

EXPOSE 80
