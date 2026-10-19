# Proyecto IA con Docker

Este repositorio contiene un servidor FastAPI desplegado dentro de un contenedor Docker.

## Cómo ejecutar el contenedor

1. Construir la imagen:
   docker build -t mi-modelo-ia:v1 .

2. Ejecutar el contenedor:
   docker run -d -p 8000:8000 --name contenedor_ia mi-modelo-ia:v1

3. Probar la API:
   Visita http://localhost:8000/ para ver la respuesta "Hola Mundo".
