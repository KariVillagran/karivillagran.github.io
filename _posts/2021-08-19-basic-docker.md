---
layout: post
title: Básico - Docker
subtitle: Conteinerización
cover-img: /assets/img/path.jpeg
thumbnail-img: /assets/img/thumb.jpeg
share-img: /assets/img/path.jpeg
tags: [docker]
---

En este articulo me gustaria retomar algunos conceptos basicos para dejarlos como notas de desarrollo.

## ¿Que es docker?

Primero la definicion de libro. *Docker is an open platform for developing, shipping, and running applications*

## ¿Que problema buscas resolver?

Siempre es importante sentarse a pensar **¿Porque necesito esto?**, razonar sobre la capacidad de la herramienta de ayudarte. Siempre hay curva de aprendizaje, pero claro, más adelante todo sera más simple.

## Ejemplo básico

Levantar un backend en node es trivial. Les comparto uno con express.

[Repositorio](https://github.com/KariVillagran/basic-node-express "basic-node-express")

Lo importante en este caso es lo que sigue. Entender como usar la CLI de docker.

### Construir la imagen

```
docker build -f ".Dockerfile" -t <your username>/basic-node-express "."
```

### Run!
```
docker run <your username>/basic-node-express
```

### Publicar 

# Referencias

* [https://nodejs.org/de/docs/guides/nodejs-docker-webapp/ ](URL "NodeJS official guide")