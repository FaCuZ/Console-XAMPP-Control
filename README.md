## Console XAMPP Control

Pequeño script para controlar el serividor local xampp desde la consola y un archivo de configuracion para Fish que mejora el aspecto de la terminal, agrega el estado de git a la dirreccion y define algunos atajos.

### Instalacion

Copiar el archivo web al directorio /usr/bin

### Comandos

	$ web start

Inicia todos los servicios (Apache, MySQL y ProFTPD)

	$ web stop

Detiene todos los servicios

	$ web status

Muestra el estado de los sevicios

	$ web restart

Reinicia los servicios

	$ web panel

Abre el panel grafico de control de servicios

	$ web net

Muestra todas las conecciones que estan en modo escucha

	$ web 80

Muestra todas las conecciones que estan usando el puerto 80


### Configuracion de Fish

Para instalarlo hay que colocar el archivo config.fish en la carpeta ~/.config/fish

Atajos:
* webdir: Ingresa a la carpeta /opt/lampp/htdocs/
* phpx: Utiliza la version de php de xampp
* artisan: Ejecuta artisar usando el php de xampp
* cxc: Idea a ejecutar el comando 'web'
* local: Idea a ejecutar el comando 'web'
