# Práctica UT6 – Despliegue de un sitio estático con GitHub Pages

## Descripción del proyecto
Este repositorio contiene un sitio web estático sencillo desarrollado como parte de la Práctica UT6 del módulo de Despliegue de Aplicaciones Web.  
El objetivo del proyecto es practicar el uso de control de versiones con Git, la publicación de un repositorio en GitHub y el despliegue automático de un sitio web mediante GitHub Pages.

El sitio está compuesto por archivos HTML, CSS y JavaScript y se publica directamente desde la rama principal del repositorio.

## Configuración de Git y conexión con GitHub

Para conectar el repositorio local con el repositorio remoto en GitHub se ha utilizado el método **HTTPS**.

### Método elegido: HTTPS

Se ha elegido la conexión mediante **HTTPS** por los siguientes motivos:
- Es el método más sencillo de configurar para usuarios principiantes.
- No requiere la generación ni gestión de claves SSH.

La conexión se realizó añadiendo el remoto `origin` con la URL HTTPS del repositorio y posteriormente realizando el primer `push` a la rama `main`.

## Publicación con GitHub Pages

El sitio web se ha publicado utilizando **GitHub Pages**, configurando el despliegue desde la rama `main` y la carpeta raíz del repositorio.  
Cada vez que se realiza un `git push`, GitHub Pages actualiza automáticamente la versión publicada del sitio.

## Autora
Andreea Neacsu
