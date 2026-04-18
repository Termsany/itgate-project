FROM nginxinc/nginx-unprivileged:stable-alpine

COPY public/ /usr/share/nginx/html/
COPY public/config.docker.js /usr/share/nginx/html/config.js
COPY nginx.conf /etc/nginx/conf.d/default.conf

EXPOSE 8080
