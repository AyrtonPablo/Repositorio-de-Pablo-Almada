# Repositorio-de-Pablo-Almada
En el presente repositorio se explicaràn y resolveràn tareas de Herramientas Computacionales

Ejercicios

1. Escribe la ruta absoluta para referirte a todos los archivos

que

inician con &quot;s&quot; y terminan con &quot;.log&quot; en el directorio

&quot;/var/log/&quot;

-$ ls –l /var/log/ s*.log

2. Escribe la ruta relativa para referirte los mismos archivos

desde

los directorios /, /usr/share, /facultad/calculo/ayudantia/ y

/usr/local/bin

-$ ls –l ../usr/share/ s*.log

-$ ls –l ../facultad/calculo/ayudantía/ s*.log

-$ ls –l ../usr/local/bin/ s*.log

3. Crea un directorio llamado miPractica que contenga dos

subdirectorios llamados usuarios y archivo y que esten en el

directorio base.

-$ mkdir –p miPractica/usuario/archivo

4. Crea un archivo llamado raizArchivos.dat en el subdirectorio

archivos del directorio miPractica que contenga el listado de

los archivos y directorios del directorio. Redirecciona la salida

de ls.

-$ >raizArchivos.dat

-$ mv raizArchivos.dat /home/ubuntu/miPractica/usuario/archivo

-$ cp /home/ubuntu/miPractica ../usuario/archivo/ raizArchivo.dat

5. A todos los directorios que haz creado asignales permisos de

lectura

y escritura para ti y solo lectura para los demas.

-$ chmod u+w,u+r,u-x,o+r,o- w,o-x miPractica

6. A todos los directorios que haz creado asignales permisos de

lectura

y escritura para ti y ningun permiso para los demas.

-$ chmod u+w,u+r,u-x,o+r,o- w,o-x miPractica

7. Crea una copia del directorio miPractica y todo su contenido

llamale ejercicios.

-$ cp miPractica ../ubuntu/ ejercicios
