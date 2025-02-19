# Construir la imagen
`docker build . -t luispinto/fastapi-app`

# Ejecutar el contenedor
`docker run -d --name web -p 8000:8000 luispinto/fastapi-app`