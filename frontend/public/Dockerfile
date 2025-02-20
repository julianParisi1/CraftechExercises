# Establece la imagen base
FROM nginx:latest

# Copia el archivo de configuracion de nginx en el contenedor
COPY default.conf /etc/nginx/conf/default.conf

# Copia el index.html en el contenedor
COPY index.html /usr/share/frontend/public/index.html

# Expone el puerto 80
EXPOSE 80

# Inicializa el servidor nginx con la directiva global daemon en off
CMD ["nginx", "-g", "daemon off;"]