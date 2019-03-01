#Firefox en Español desde terminal GNU/Linux para Parrot Os 
-
  Lo primero que se debe de hacer es eliminar las versiones antiguas de firefox o las que trae por defecto en el idioma inglés
  
  Eliminaremos desde la terminal en modo root los archivos ubicados en el directorio /lib todo lo referente a firefox
  #/usr/lib
  -
  #cd /usr/lib 
  -
  #rm -r firefox
  -

  ----------------------- 
 Una vez echo esto también buscamos en el directorio /usr/bin y eliminamos lo referente a firefox
 
 #/usr/bin
 -
 #cd /usr/bin
 -
 #rm -r firefox
-

 echo esto procedemos a limpiar paquetes obsoletos
 
 #apt-get autoremove
 -
 #apt-get upgrade
---------------------------------
 después nos dirigimos a la pagina oficial de Mozilla español https://www.mozilla.org/es-ES
seguimos los siguientes pasos:
Descarga Firefox desde esta página de descarga directamente en tu directorio de inicio o en el que gustes :)
Abre un Terminal y ve a tu directorio de inicio: cd ~
Extrae el contenido del archivo descargado: 
#tar xjf (nombre del tar descargado)
-
un ejemplo seria:
#tar xjf firefox-*.tar.bz2
-----------------

Echo esto para iniciar Firefox, ejecuta el script firefox en la carpeta firefox: ~/firefox/firefox 
esa carpeta se creo dentro del desempaquetamiento del tar de firefox y listo :) ya tienes firebox en español
 (NO necesariamente es en la distribución Parrot Os, si no en cualquier distro linux al cual la configuracion del español no quiera funcionar)
