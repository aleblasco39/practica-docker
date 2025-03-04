# practica-docker
Esta practica consiste en subir un archivo docker-composer.yml con un archivo .env en el que hemos descritos las variables de entorno para el archivo dockerfile.

El archivio docker-composer consiste en un contenedor para el backend y otro para el frontend, el backend consiste en una base de datos MySQL y un gestor de base de datos PHPMYADMIN, el frontend consiste en un bloque WordPress de PHP.

Una vez tengas descargado el archivo, abrimos la consola BASH si estas en Windows, o el terminal en Linux y ejecutamos el siguiente comando:

_docker compose up -d_

Después de que levantemos los archivos, iremos al 192.168.10.10 y podremos ver la página wordpress levantada y si se va a  192.168.20.10/phpmyadmin, deberías poder acceder al gestor de la base de datos.

