FROM nginx:latest

COPY default.conf /etc/nginx/conf/default.conf

COPY index.html /usr/share/frontend/public/index.html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]