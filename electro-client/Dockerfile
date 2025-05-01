FROM nginx:1.28.0-alpine

COPY nginx.conf /etc/nginx/nginx.conf

WORKDIR /usr/share/nginx/html

ADD build /usr/share/nginx/html
