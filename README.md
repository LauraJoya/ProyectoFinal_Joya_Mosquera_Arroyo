# ProyectoFinal_Joya_Mosquera_Arroyo
Como clonar este repositorio de GitHub con el proyecto Lola Club completo y retomar su desarrollo localmente siguiendo unos pocos pasos:
1)	Es necesario crear un directorio en su equipo, ya sea por medio de la consola del sistema de GitHub “Git Bash” o directamente haciendo clic en “crear nueva carpeta” donde el usuario lo desee.

Si decide crearlo por medio de la consola digite los comandos:

    C:\>mkdir nombre_del_directorio
    C:\>cd nombre_del_directorio (esto para posicionarse dentro del directorio creado).

2)	Luego, en la consola de “Git Bash” se digita el siguiente comando:
    C:\nombre_del_directorio>git clone https://github.com/LauraJoya/ProyectoFinal_Joya_Mosquera_Arroyo.git

3)	Se revisa la carpeta, digitando:
    C:\nombre_del_directorio\LolaClub>git status

    Realizando esto, los documentos se deben encontrar de manera correcta en el directorio que el usuario creo.

4)	Cuando el proyecto ya está clonado y el usuario cuenta con él en su dispositivo local, para la visualización completa del proyecto en un navegador web, se tiene que hacer uso de un servidor web, este se obtiene gracias al uso de NodeJS, el usuario debe descargar la última versión del programa, el cual incluye NodeJS y npm, este último es el que nos permitirá instalar paquetes. Luego, cuando esté descargado NodeJS nos dirigimos a la ventana de comandos de esta plataforma y digitamos el comando npm install –g serve, luego nos posicionamos en el directorio del proyecto y ejecutamos el comando serve . , esto nos proporcionará una dirección localhost la cual debemos colocar en el navegador web que se esté utilizando (de preferencia Google Chrome).
