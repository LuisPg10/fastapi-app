# Construir la imagen
`docker build <ubicacion del Dockerfile> -t luispinto/fastapi-app`

# Ejecutar el contenedor
`docker run -d --name web -p 8000:8000 luispinto/fastapi-app`