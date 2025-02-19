# Establece la imagen base
FROM node:18

# Establece el directorio de trabajo dentro del contenedor
WORKDIR /usr/src/app

# Copia las dependencias de React
COPY package.json package-lock.json ./

# Instala las dependencias
RUN npm install

#Copia el codigo fuente del frontend dentro del contenedor
COPY . .

#Ejecuta la aplicacion
CMD ["npm", "start"]