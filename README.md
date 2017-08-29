# Ejercicio UTB

### Configuración de proyecto 
En la configuración de nuestro proyecto se necesitarán dos carpetas que se crearán como "Volumenes" persistente de cada una de las partes importantes del mismo.
	
	* mysql 
	* wp-content

 ##### - mysql (folder):
 Es el directorio en el que haremos persistente nuestros datos almacenados en el docker hacia esta carpeta.
 
 ##### - wp-content (folder):
 Es el directorio en el que se guardará la configuración de nuestra aplicación Wordpress. La configuración de nuestro proyecto "linkeará" la carpeta **/var/www/html/wp-content** con la carpeta en nuestra raíz del proyecto **wordpress**.
 
 
 #### Imágenes
 
 ##### -mysql (imágen):
 En el docker-compose de nuestra aplicación usaremos la imagen de [mariadb:10.3.0](https://github.com/docker-library/mariadb/blob/198f04b24ca6f668357106355b03d38d1f3234bc/10.3/Dockerfile) 
 
 ##### -wordpress (imágen):
Nuestra aplicación se basará en la imagen [wordpress:4.8.1-apache](https://github.com/docker-library/wordpress/blob/7902c5f856c7fbc20dd70762bef324158328dcff/php5.6/apache/Dockerfile) 


 
 
