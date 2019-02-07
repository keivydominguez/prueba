#### Tutorial de git
_HOla lo que haremos es subir archivos en github_

Lo primero sera crear una cuanta en **github**. 

<https://github.com/>

Una vez adentro en la parte de arriba a la izquierta le picamos y nos mostrara unos menu y le picaremos en donde dice **your repositories** y le picaremos en el boton verde que dice **New** aqui ya crearemos nuestro repositorio.

1. En **Repository name** pondremos el nombre de como se llamara el repositorio.
2. En **Description** es opcional 
3. Tienes que ponerlo en **public** porque si selecionamos **private** tendremos que pagar.
4. seleccionamos la casilla.
5. Picamos en el boton verde **create repository** para ya finalizar.

Nos aparecera unos codigos y un link, abrimos nuestro terminal y introduciremos estos codigos.

1. git init
2. git add archivo.md o . **el punto sube todo lo que hay en esa carpeta o puedes espesificar lo que vas a subir**
3. git commit -m "Mi primer commit"
4. git remote add origin <https://github.com/keivydominguez/prueba> **aqui ira el link de tu repositorio**
5. git push -u origin master
6. nos pedira nuestro usuario de gituhb y nuestra contrasena
7. listo ya subiste tu primer repositorio 

Ahora crea un nuevo archivo y lo vamos a subir a github.

1. git status **esto nos dira si hay archivos para subir**
2. git add archivo-2.md **seleccionaremos el archivo que creamos**
3. gi commit -m "second arcchivo" **las etiquetas procura que sean en ingles y claras**
4. git push origin master
5. nos pedira nuestro usuario de gituhb y nuestra contrasena
6. y listo ya subimos nuestro segundo archivo 

Y a si es para cuando quieras subir otros archivo, imagenes o carpetas.
_Espero que de haya gusto y nos vemos para la otra que tengas un bonito dia_


