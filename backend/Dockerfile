# Establece la imagen base
FROM python:3.10

# Establece el directorio de trabajo dentro del contenedor
WORKDIR /usr/src/app

# Copia las dependencias de Django
COPY requirements.txt .

# Instala las dependencias
RUN pip install --no-cache-dir -r requirements.txt

#Copia el codigo fuente del backend dentro del contenedor
COPY . .

#Corre el servicio backend en gunicorn
CMD ["gunicorn", "core.wsgi:application", "--bind", "0.0.0.0:8000"] 