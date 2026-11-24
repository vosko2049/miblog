---
layout: post
title: "Mi primer contenedor Docker"
date: 2026-10-15 19:00:00
categories: contenedores
tags: [docker, nginx]
image: assets/images/posts/docker/portada-docker.jpg
imagen_alt: "Portada del post sobre Docker"
---
![page.imagen_alt]({{page.image | relative_url}}) 
Levantamos un servidor Nginx dentro de un contenedor en un solo comando.
## Arrancar el contenedor
```bash
docker run -d --name web -p 8080:80 nginx
curl -I http://localhost:8080
```
## Cómo funciona
(insertar imágen docker-arquitectura.png).