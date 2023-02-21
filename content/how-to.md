---
title: "Como usar esta web"
date: 2023-02-21T18:31:50Z
draft: false
---

## Sobre el CMS y su uso mediante Dockerfile

El programa Hugo se instala como un binario. Este binario ejecutable implementa un servidor HTTP y un generador de páginas estáticas que nos permitía servir a través del servidor deseado. 

Para este proyecto generaremos una plantilla de Hugo y usaremos la imagen de Docker `klakegg/hugo` para ejecutarla durante el desarrollo y generar los archivos estáticos al finalizar.

Usamos el comando para iniciar el servidor de desarrollo en el directorio actual.

```shell
$ docker run --rm -it -v $(pwd):/src -p 1313:1313   klakegg/hugo:latest-ext server
```

Y usaremos el siguiente comando para crear todos los archivos estáticos de la web en la carpeta /public:

```shell
$ docker run --rm -it -v $(pwd):/src -p 1313:1313   klakegg/hugo:latest-ext
```
[[Top]](#top)