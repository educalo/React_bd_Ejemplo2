1.- Este proyecto funciona con la versión node 16.0.0, podemos utilizar la utilidad nvm para poder cambiar la versión de node.

2.- Para instalar nvm accedemos a la siguiente web https://github.com/coreybutler/nvm-windows#installation--upgrades y la descripción en el apartado Overview descargamos la aplicación.

3.- para saber la versión de node instalada dentro de la terminal ponemos node -v

4.- nvm --help para ayuda relacionada con nvm

5.- nvm ls para ver el listado de versiones instaladas de node.

6.- nvm install [VERSION NODE] para instalar una versión concreta de node, en nuestro caso pondríamos nvm install 16.0

7.- nvm use [VERSION_NODE] para establecer una version de node en uso, en nuestro caso nvm use 16.0

8.- nvm ls para ver la lista de versiones de node que tenemos, aparecerá con un asteristco la utilizada actualmente.

9.- Una vez que tengamos en uso node 16.0 tenemos que hacer dos cosas: arrancar la parte back y arrancar la parte client


10.- Creamos dentro del XAMPP una nueva base de datos que se llama samus y luego importamos el fichero samus.sql incluida en el proyecto

11.- Dentro de Visual Studio code y dentro de la carpeta back añadimos en una terminal el comando npm install y luego npm start y debe aparecer un mensaje de consola "Servidor activo"

12.- Abrimos una nueva terminal, entramos en la parte client y añadimos el comando npm install y npm start

13.- Se nos abrirá una pantalla en nuestro navegador por defecto que para entrar habrá que escribir login: samus contraseña: 123456





