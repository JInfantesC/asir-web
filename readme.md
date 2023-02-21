# asir-web

Ejemplo de web en Hugo 

Para este proyecto generaremos una plantilla de Hugo y usaremos la imagen de Docker klakegg/hugo1 para ejecutarla durante el desarrollo y generar los archivos estáticos al finalizar.
Usamos el comando para iniciar el servidor de desarrollo en el directorio actual.


```shell
$ docker run --rm -it -v $(pwd):/src -p 1313:1313 klakegg/hugo:latest-ext server
```

Y usaremos el siguiente comando para crear todos los archivos estáticos de la web en la carpeta /public:

```shell
$ docker run --rm -it -v $(pwd):/src -p 1313:1313 klakegg/hugo:latest-ext
```