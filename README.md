
Repository dedicated to list, explain and give examples of some commands that were used on the course Operative Sistems on Ulacit.

| Comando | Descripción | Ejemplo de uso |
|--|--|--|
| `pwd` | Muestra el nombre de su directorio actual, lo que puede ser útil al navegar por el sistema de archivos. | `pwd` En este caso para ubicarnos entre los archivps como: /home/usuario. 
| `cd <ruta de directorio>` | Se usa para cambiar el directorio de trabajo actual de un usuario. Puede ser para subir un nivel en el sistema de archivos o e le puede dar un directorio como argumento para cambiar el directorio de trabajo. | `cd`(para ir al home por defecto del usuario)`cd ..` (para devolverse o salir desde la carpeta en la que estás posicionado), `cd <carpeta>` (para ingresar a un folder) y `cd /home/usuario/public_html` (para saltar entre directorios). |
| `clear` | Limpia la pantalla de la sesión de consola actual. | `clear` muestra toda la información (gracias al flag `-a`) sobre 
| `ls <directorio>` | Lista los archivos y directorios que están dentro de un directorio. Si no se pasa ningún directorio cómo parámetro se listan los del directorio actual. | `ls ~/Ulacit` para mostrar todas las carpetas y archivos dentro de la carpeta Ulacit. |
| `cp <origen> <destino>` | Copia un archivo (o directorio si se usa el flag `-r`) de un origen a un destino. | `cp -r ~/Ulacit/* ~/` para copiar todo el contenido de la carpeta llamada Ulacit al home del usuario actual. |
| `echo` | Imprime en pantalla una cadena de texto. | `echo "Hola"` imprimiría Hola en la salida de la terminal. |
| `htop` | Muestra la lista de procesos y una aplicación de modo de texto para la supervisión del sistema en tiempo real. |` 
| `adduser <nombre de usuario>` | Crea un nuevo usuario |
| `passwd <nombre de usuario>` | Cambia la contraseña de un usuario |
| `history` | Historial de comandos |
| `sudo su` | Cambiar  a super usuario |
| `mount `| Monta un sistema de archivos |
| `nano <archivo> `| Crea o modifica un archivo de texto |
| `echo <texto> `| Muestra texto en la terminal |
| `cat `| Muestra lo que hay en un archivo de texto |
| `sudo apt upgrade <software name>` | Instala todas las actualizaciones disponibles de los paquetes instalados en tu equipo. | 
| `sudo apt apt-get upgrade <software name>` |  Igual al anterior pero este no elimina las versiones antiguas de los paquetes instalados o actualizables del sistema que ya no se necesitan al realizar la actualización. |  
| `apt-get <nombre programa>` | Instala software o programas adicionales |
| `apt purge -y <nombre programa>` | Desinstala un programa instalado |
| `cp` | Copia un archivo o carpeta |  
| `mv` | Mueve un archivo o carpeta |  
| `rm` | Elimina un archivo |
| `rmdir` | Elimina un directorio |
| `chmod` | Modifica los permisos de un archivo |
| `systemctl start <proceso> `| Inicia un proceso |
| `systemctl restart <proceso> `| Reinicia un proceso |
| `systemctl stop <proceso> `| Detiene un proceso |
| `systemctl enable <proceso> `| Habilita un proceso |
| `systemctl status <proceso> `| Muestra el estado un proceso |
| `kill | Finaliza un proceso `|  
| `wget <página web> `| Permite descargar archivos de Internet |  
| `docker run hello-world `| Verifica que docker esté funcionando correctamente | 
| `docker search <imagen> `| Busca una imagen de docker | 
| `docker pull <imagen> `| Instala una imagen de docker | 
| `docker docker run <imagen> `| Ejecuta una imagen de docker | 
| `docker docker images `| Muestra todas las imágenes instaladas | 
| `docker ps -a `| Muestra el estado de las imágenes | 
| `docker start `| Inicia un contenedor | 
| `docker stop `| Detiene un contenedor |
| `docker rmi `| Elimina imagen instalada |  
| `docker rm <id> `| Elimina contenedor |  
| `docker run --rm <imagen> `| Elimina contenedor |
//Laboratorio 04 Manjaro Linux y Comandos
| `sudo pacman -S` |  Se utiliza para instalar uno o varios paquetes en sistemas basados en Arch Linux  | `sudo pacman -S <nombre_paquete1> <nombre_paquete2>`. |
| `sudo pacman -Sy` | Imprime en pantalla una cadena de texto. | `echo "Hola"` imprimiría Hola en la salida de la terminal. |
| `sudo pacman -S unrar zip unzip gzip bzip2` | Se utiliza para instalar una serie de utilidades de compresión y descompresión en sistemas basados en Arch Linux. | `echo "Hola"` imprimiría Hola en la salida de la terminal. |
| `echo` | Imprime en pantalla una cadena de texto. | `echo "Hola"` imprimiría Hola en la salida de la terminal. |
