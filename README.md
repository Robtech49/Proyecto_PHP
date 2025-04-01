Proyecto PHP - Despliegue de Imagen de un Lobo

Descripción

Este proyecto en PHP muestra el código fuente necesario para desplegar la imagen de un lobo en un servidor web.

Prerrequisitos

Para ejecutar este proyecto, asegúrese de tener instalados los siguientes paquetes en su sistema Ubuntu.

1. Instalar GIT

Git es necesario para la gestión del código fuente.

sudo apt update && sudo apt install git -y

Verifique la instalación con:

git --version

Ejemplo de salida:

git version 2.43.0

2. Instalar Apache 2

Apache es requerido para servir archivos PHP en el servidor.

sudo apt install apache2 -y

Verifique la instalación con:

apache2 -v

Ejemplo de salida:

Server version: Apache/2.4.58 (Ubuntu)
Server built:   2024-10-02T12:40:51

3. Instalar PHP

PHP es el lenguaje utilizado en este proyecto.

sudo apt install php -y

Verifique la instalación con:

php -v

Ejemplo de salida:

PHP 8.3.6 (cli) (built: Dec  2 2024 12:36:18) (NTS)

Uso

Una vez instalados los prerrequisitos, copie el archivo PHP del proyecto en el directorio de Apache.

sudo cp lobo.php /var/www/html/

Asegúrese de que el servicio Apache esté activo:

sudo systemctl start apache2

Luego, abra un navegador y acceda a:

http://localhost/lobo.php

Esto mostrará la imagen del lobo en su navegador.

Contribución

Si desea contribuir a este proyecto, puede clonar el repositorio, realizar cambios y enviar un pull request.

git clone <URL_DEL_REPOSITORIO>
cd proyectoPHP

Licencia

Este proyecto está bajo la licencia MIT. Para más detalles, consulte el archivo LICENSE.
