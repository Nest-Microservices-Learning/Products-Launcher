## Dev

1. Clonar el repositorio
2. Crear un .env basado en el .env.template
3. Ejecutar el comando `git submodule update --init --recursive` para reconstruir los sub-moduloss
4. Ejecutar el comando `docker compose -f docker-compose.prod.yml build && docker compose -f docker-compose.prod.yml up`
