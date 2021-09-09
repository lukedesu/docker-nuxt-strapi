# docker-nuxt-strapi

## Proyecto multi contenedor para google cloud compute engine


Este proyecto incluye 3 servicios

- Nuxt versión 2.x (frontend)
- Strapi versión 3.x (backend)
- Mysql 5.7 (mysql)

Cada servicio se creará en una imagen Docker, que se ejecutaran en contenedores docker en una máquina virtual o instancia de Google Cloud Compute Engine.

Para correr los contenedores en la máquina virtual usaremos un sistema optimizado para ello, llamado Container Optimized OS de Google. Se suele abreviar como COS.

Se puede correr un contenedor por cada servicio de forma individual o, si estamos en nuestra máquina local, usar docker compose.

También se podría usar docker-compose en la máquina virtual pero lleva un poco más de trabajo.

Para transportar las imagenes usaremos un repositorio de Google Cloud Artifacts. Es recomendable crearlas localmente y pushearlas al repositorio.

[VER TUTORIAL COMPLETO](./tutorial.md)

