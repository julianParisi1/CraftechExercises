*** INSTRUCCIONES PARA COMPILAR/DESPLEGAR LA APLICACION ***

REQUISITOS PREVIOS:

Instalar Docker y docker-compose o Docker Desktop. (recomiendo Docker Desktop)

-------------------------------------------------------------------------------------------------------------------------

PASOS:

1. Descargar el proyecto y guardarlo en algun directorio de la computadora: https://github.com/julianParisi1/CraftechExercises

2. Abra una instancia de linea de comandos (Bash, Windows PowerShell, etc)

3. Navegue hasta el directorio donde tiene guardado el proyecto (utilizando el comando CD) -- Ej: cd C:\Users\Usuario\Desktop\Laburo\Repos

4. Acceda a la carpeta backend -- cd backend

5. Ejecute el comando docker-compose up --build

-------------------------------------------------------------------------------------------------------------------------

ORGANIZACION DE ARCHIVOS DE LOS EJERCICIOS

PUNTO 2:

- El docker-compose del punto 2 se encuentra en /backend (django, react)
- 
- Los Dockerfiles para este punto son dos y se encuentran en /backend(django) y /frontend(react)


PUNTO 3:

- El docker-compose del punto 3 se encuentra en /frontend (nginx)

- El Dockerfile de este punto se encuentra en /frontend/public

- El archivo deploy.yml en /.github/workflows es el que configura el pipeline CI/CD

-------------------------------------------------------------------------------------------------------------------------

RECURSOS UTILIZADOS:

- Curso basico DevOps - Craftech

- Youtube:

	- https://www.youtube.com/watch?v=a5qkPEod9ng  -- Tutorial que explica como construir un archivo .yml para la pipeline CI/CD, como definir jobs, etc.
	- https://www.youtube.com/watch?v=4Dko5W96WHg&t=4114s -- Tutorial basico de funcionamiento y comandos de Docker.

- StackOverflow: Utilizado mas que nada para buscar informacion y soluciones a errores puntuales.

- ChatGPT: Utilizado como un asistente para consultas mientras desarrollo y como fuente de informacion sobre tecnologias o conceptos.
           Lo considero muy util por su capacidad de recolectar informacion y presentarla de una manera estructurada y legible.