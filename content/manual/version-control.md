---
title: "Control de versiones"
date: 2023-02-21T18:31:37Z
draft: false
weight: 1
summary: El control de versiones es indispensable para cualquier desarrollador de software. Aprende a usarlo a continuación.
---

Origen del articulo: [https://www.atlassian.com/es/git](https://www.atlassian.com/es/git)

# Principios básicos de Git

Git es un sistema de control de versiones gratuito y de código abierto, creado originalmente por Linus Torvalds en 2005. A diferencia de los antiguos sistemas centralizados de control de versiones, como SVN y CVS, Git está distribuido: cada desarrollador tiene el historial completo de su repositorio de código de manera local. De este modo, la clonación inicial del repositorio es más lenta, pero las operaciones posteriores, como commit, blame, diff, merge y log son mucho más rápidas.

Git incluye las funcionalidades de crear ramas y fusiones y reescribir historiales de repositorios, lo cual ha dado como resultado muchas herramientas y flujos de trabajo innovadores y eficaces. Las solicitudes de incorporación de cambios son una herramienta popular con la que los equipos pueden colaborar en las ramas de Git y revisar con eficacia el código de los demás. Git es el sistema de control de versiones más utilizado en el mundo hoy en día, y se considera el modelo actual de desarrollo de software.

# Funcionamiento de Git

Básicamente, Git funciona del siguiente modo:

- Crea un "repositorio" (proyecto) con una herramienta de alojamiento de Git (por ejemplo, Bitbucket)
- Copia (o clona) el repositorio a tu máquina local
- Añade un archivo a tu repositorio local y confirma ("commit") los cambios
- Envía ("push") los cambios a la rama principal
- Haz cambios en tu archivo con una herramienta de alojamiento de Git y confírmalos
- Extrae ("pull") los cambios a tu máquina local
- Crea una rama ("branch", versión), haz algún cambio y confírmalo
- Abre una solicitud de incorporación de cambios ("pull request": propón cambios a la rama principal)
- Fusiona ("merge") tu rama con la rama principal



[[Top]](#top)