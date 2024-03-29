# Creación de un paquete NPM. Práctica 2 de SYTW

Durante la siguiente práctica trataremos de crear un paquete de NodeJS que nos permita automatizar las tareas de la anterior práctica, [tareas iniciales](https://github.com/ULL-ESIT-SYTW-1617/tareas-iniciales-rafadanipedro), en la que teníamos que publicar un libro en Gitbook con los pasos a realizar en la práctica.

Además de esto, también publicaremos el paquete en la página de npm bajo el usuario [rafadanipedro](https://www.npmjs.com/~rafadanipedro).

## Instalación del paquete
Para instalar el paquete debemos de ejecutar el siguiente comando:
`npm --global install gitbook-start-rafadanipedro`

También podemos instalarlo de manera local si queremos eliminando el argumento `--global`.

## Uso del paquete
Para utilizar el paquete solo tenemos que ejecutar el comando `gitbook-start` seguido de los siguientes argumentos:

 `--author`: especifica el autor del libro. Por defecto es el nombre de usuario de GitHub.  
 `--email`: especifica el email del autor del libro. Por defecto es el correo de usuario de git.  
 `--license`: especifica la licencia del libro. Por defecto es "MIT".  
 `--repo`: especifica la direccion del repositorio de GitHub. Por defecto es "https://github.com/'+nombreUsuario/'+nombreRepo".  
 `--ghPages`: especifica la direccion en la que se encuentran las gh-pages generadas. Por defecto es "http://'+nombreUsuario.github.io/'+nombreRepo".  
 `--name`: especifica el nombre del libro. Por defecto este argumento es obligatorio.  
 `--title`: especifica el titulo del libro. Por defecto es el mismo que el nombre del libro.  
`--description`: especifica la descripcion del libro. Por defecto es "Descripcion breve del Gitbook".  
 `--outputDirName`: nombre del directorio a crear. Por defecto es el nombre del libro.

Es obligatorio especificar un nombre para el libro, ya que es el unico argumento obligatorio.

Ejemplo: `gitbook-start mi_libro --author Joselito --email joselito@chuchu.com`

## Enlace al paquete en npm
 * [Paquete publicado en npm](https://www.npmjs.com/package/gitbook-start-rafadanipedro)

## Descripción de la práctica
 * [Gitbook de la práctica](https://casianorodriguezleon.gitbooks.io/ull-esit-1617/content/practicas/practicanm.html)

## Páginas personales
 
Pinchando sobre las imágenes podrás acceder a nuestras páginas personales.

<a href='https://rafaherrero.github.io' target='_blank'><img src='https://avatars2.githubusercontent.com/u/11819652?v=3&s=400' border='0' alt='postimage' width='100px'/></a> <a href='https://danielramosacosta.github.io/' target='_blank'><img src='https://avatars2.githubusercontent.com/u/11427028?v=3&s=400' border='0' alt='postimage' width='100px'/></a> <a href='https://alu0100505078.github.io/' target='_blank'><img src='https://avatars3.githubusercontent.com/u/14938442?v=3&s=400' border='0' alt='postimage' width='100px'/></a>
