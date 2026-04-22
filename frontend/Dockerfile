FROM nginxinc/nginx-unprivileged:stable-alpine

COPY public/ /usr/share/nginx/html/
COPY public/config.docker.js /usr/share/nginx/html/config.js
COPY nginx.conf /etc/nginx/templates/default.conf.template

EXPOSE 8080
