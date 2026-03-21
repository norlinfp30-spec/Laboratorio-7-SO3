Módulo-7-SO3-CLI Comandos utilizados en Laboratorio Módulo 7 - Sistemas Operativos III

Este repositorio contiene los comandos prácticos con los cuales se desarrollaron las prácticas de el septimo laboratorio de la asignatura Sistemas Operativos III, impartida por el profesor Adrian Alcantara.

En el mismo se desarrollaron los siguientes temas:

Practica 1: compartir archivos entre linux utilizando NFS
• Instale NFS en el servidor, cree un directorio llamado OS3 que contenga 100 archivos dentro llamados Adrian [1..100].txt que sera el directorio que se utilizara para compartir.
• Asigne los permisos de carpeta y de usuario para que pueda ser acesible por otros usuarios .
• Configure los exports para definer que directorios y con que permisos seran compartidos.
• En la maquina Linux cliente instale el cliente de NFS, y monte el directorio compartido desde el servidor NFS.
• Agrega una entrada en el archivo /etc/fstab para que el directorio compartido se monte desde que se reinicie la pc (muestre la prueba de que funciona visualizando los archivos en la VM cliente y luego reiniciando la VM y mostrando como se monta automaticamente al subir el Sistema)

Practica 2: Creacion de fileserver compatible con Windows utilizando SAMBA
• Instalar SAMBA y habilitar el servicio.
• Crear Carpeta Compartida, Crear Usuarios y Grupos y dar los permisos necesarios a la carpeta compartida.
• En la carpata de Samba crear 100 archivos llamados adrian(adrian1, adrian2.....adrian100).
• En el sistema Windows, mapear un nuevo disco virtual y especificar la carpeta de samba como disco virtual donde se visualisaran los 100 archivos.
• Ingresar al archivo Adrian99 desde el disco mapeado en windows y agregar la frase "el zumzum de la carabela", guardar y regresar a la carpeta desde linux y validar que la modificacion se hara realizado satisfactoriamente.

Practica 3: Creacion de controlador de Dominio con cliente Windows
• Crea un usuario en Linux llamado lanegracubana, como contrasena su matricula y agregarlo a samba.
• Crear un dominio en samba4 llamado SO3.inet
• Agregar la VM de Windows al dominio con SAMBA y que autentique con el usuario creado en el punto anterior.

Este es el enlace a la lista de reproduccion en youtube: ↓
https://youtube.com/playlist?list=PLpcZGYtY2vZbfzpCgk_FtF7Dd7Thl-8Ba&si=YxfL3Sl_Cl-mAGU8
