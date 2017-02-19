Universidad Icesi

# Informe comandos CentOS

 Carolina Zúñiga: A00315292

## Comandos Linux

![1] (https://github.com/carozuniga/so-bash/blob/master/IMAGES/history.PNG)

## Solución a las preguntas 

1. directorios en la raiz de linux CentOS:

  -/bin
  significa binary, este directorio contiene la mayoría de los programas  esenciales del sistema. ejemplos de los archivos que se encuentran en este direcotrio son: cat (permite visualizar el contenido de uno o varios archivos en la pantalla), chmod (modifica los permisos de un archivo), chgrp, mv, echo, entre otros.
  
  -/dev 
  Contiene archivos especiales del sistema, conocidos como controladores de dispositivo (device drivers), los cuales se usan para acceder a los dispositivos del sistema y recursos, como discos duros, modems, memoria, etc. algunos ejemplos: 
    /dev/hda Disco primario.
    /dev/hdb Disco esclavo del anterior.
    /dev/mouse Se utiliza para la lectura de entrada del mouse.
    /dev/hdc Disco primario en otro slot.
    /dev/hdd Disco esclavo del segundo slot.
    /dev/fd0 Generalmente son los floppy disk.
    
  -/etc 
  Este directorio está reservado para los ficheros de configuración y arranque del sistema Linux. En este directorio no debe aparecer ningún fichero binario (programas). Bajo éste deben aparecer otros subdirectorios como por ejemplo:

    /etc/X11 Ficheros de configuración de X Window.
    /etc/skel Ficheros de configuración básica que son copiados al directorio del usuario cuando se crea uno nuevo.
    /etc/conf.modules Archivo donde se indica que modulos se anexan al kernel en el momento del boot.
    /etc/services Tabla en la cual se describen los servicios a los que tienen acceso los usuarios y por qué puertos trabajan.
    /etc/passwd Contiene información sobre los usuarios, como login, nombre y otra información que el administrador quiera agregar.
    /etc/shadow Almacena los password en forma encriptada y las fechas de expiración de los mismos.
    /etc/sysconfig Almacena archivos de configuraión de del sistema, por ejemplo el idioma, el tipo de teclado.
  
    
