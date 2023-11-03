# Repo practica-Github

## 01-pruebagit
Prueba de git para practicar lo siguiente:
* Creación de repositorio
* Añadir nuevo archivo

Se practicó la creación de repositorio remoto en la web de github, y se copió su respectiva URL para usarlo posteriormente en la terminal.

Además se practican los _principales comandos en la terminal_ para añadir el repo local en el repo remoto, haciendo uso de los siguientes comandos:
* ```git init``` para crear subdirectorio . git en el directorio del trabajo actual.
* ```git remote add origin LINK``` para agregar el repositorio remoto, donde el link se toma del repo remoto creado en el perfil de github.
* ```git status``` para verificar cuales archivos han sido modificados.
* ```git add .``` para añadir todos los archivos modificados.
* ```git commit -m "MENSAJE"``` nos permite hacer el commit y dejar un MENSAJE que indique cual fue el cambio realizado en el repo. Captura una instantánea de los cambios preparados en ese momento del proyecto.
* ```git push origin RAMA``` se cargan los cambios en el repo remoto.

## 02-pruebaderamas
Nos permitió practicar la creacion y eliminación de ramas en local, haciendo uso de los siguientes comandos:
* ```git checkout -b RAMA``` que creó una nueva rama con el contenido de la anterior.
* ```git branch -d RAMA``` para eliminar la rama.
