<p align="center">
  <img src="https://www.utng.edu.mx/assets/principal/logo.png" width="300">
</p>

# Proyectos de Despliegue y Contenerización con Docker

## Descripción General

Durante estas prácticas se desarrollaron y desplegaron diferentes aplicaciones web utilizando Docker y Docker Compose. Se trabajó con tecnologías frontend y backend como Angular y NestJS, integrando bases de datos MySQL y MongoDB dentro de entornos contenerizados.
Todo esto en la materia de "Automatización de infraestrucutura Digital 1"

## Tecnologías Utilizadas

- Docker
- Angular
- Nginx
- MySQL
- MongoDB
- PostgreSQL
- phpMyAdmin
- TypeScript
- Mongoose

## Proyectos Desarrollados

### Sistema de Ventas
Aplicación web compuesta por un frontend Angular, un backend NestJS y una base de datos MySQL administrada mediante phpMyAdmin.

### Angular Monster App
Aplicación Angular desplegada mediante Docker utilizando Nginx como servidor web para la publicación de archivos estáticos.

### Nest Pokémon API
API REST desarrollada con NestJS y MongoDB para la gestión de información de Pokémon obtenida desde una API externa.

## Comandos Utilizados

### Gestión de Repositorios

```bash
git clone https://github.com/edomenzain/angular-monster-app.git
git clone https://github.com/edomenzain/nest-pokemons-app.git
```

### Construcción de Imágenes Docker

```bash
docker compose build
docker compose up -d --build
```


### Administración de Docker Compose

```bash
docker compose up -d
docker compose down
docker compose down -v
docker compose restart
```



## Resultados Obtenidos

-

## Conclusión

Docker y Docker Compose permitieron simplificar el despliegue, administración e integración de múltiples servicios dentro de un mismo entorno, facilitando la portabilidad, escalabilidad y mantenimiento de las aplicaciones desarrolladas.

## Autora
Jocelyn Gonzáles Ramírez 
