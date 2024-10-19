FROM nginx:latest
LABEL authors="Daniel"

COPY softy-pinko-front-end /var/www/html/softy-pinko-front-end
COPY softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
