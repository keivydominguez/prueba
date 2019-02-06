# BIENVENIDO 
_Esta carpeta esta subido todas las pruebas y ejemplos del curso_ 

#### Que significan y para que sirven las siguientes palabras clave

- local
- remote: apunta a la dirección donde deseáis subir el nuevo material.
- init:  inicia git al interno de la carpeta.
- clone: Clonar un repositorio.
- add: añade el documento o carpeta.
- commit: describe los cambios realizados.
- push: subís los cambios a GitHub.
- pull: baja los cambios del repositorio remoteo a nuestra copia en local.
- merge: Guarda los cambios desde la rama.
    
#### las fases de GIT
1. Working Directory
Aquí es donde podemos hacer cualquier cambio y no afectar nuestro repositorio en lo absoluto.
*codigo*
git add nombreDelArchivoModificado.js

2. Staging Area
Aquí es donde le podemos dar nombre a nuestra nueva versión. Y crear una “copia” de cómo quedaría nuestra nuestro repositorio en producción.
*codigo*
git commit -m "Nombre del la nueva versión

3. Git Repository
Una vez que el código esta confirmado ya esta listo para sincronizarse con el servidor de Git (github, bitbucket,etc). 
*codigo*
git push -u origin master

#### ¿Que son las cosas que NO se deben hacer en un repositorio de GIT?

- Nunca hacer git push --force porque cuando nuestro repositorio local no está sincronizado es decir actualizado con el repositorio central, este último no podrá hacer merge y nos devolverá un mensaje de error.

- Nunca subir archivos binarios porque los archivos de texto son un punto clave aquí, pues los cambios en esta clase de archivos son fácilmente detectables, pero es casi imposible para datos binarios.

- Nunca usar git pull porque si hacemos git pull no tendremos oportunidad de ver qué clase de cambios estamos tratando de incorporar (haciendo pull).

#### ¿A que año debía volver Marty McFly para reestablecer la linea de tiempo?
