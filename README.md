# taller 1
**Nombre:** Carlos Andrés Afanador C  
**Código:** A00054652

## Descripcion: En este taller se pudieron conocer la utilidad de los directorios, que hasta ahora eran desconocidos, ademas de muchos comandos nuevos.

## Soluciones

### 1.
| Directorio   | Archivo ejemplo | Descripción del contenido del directorio  |
|------|------|------|
| bin | gzip: utilidad de GNU para comprimir | contiene los archivos binarios del sistema |
|------|------|------|
| sbin | dnsmasq: proporciona servicios como caché DNS | contiene los archivos binarios del sistema reservados para el administrador |
|------|------|------|
| boot | grub: incluye los archivos del boot-up (incluye imágenes y sonidos) | contiene los archivos que necesita el sistema para hacer boot, tiene el kernel |
|------|------|------|
| dev | ttyS0: primer puerto serial | archivos relacionados con el hardware del sistema |
|------|------|------|
| etc | email-address: contiene el dirección de correo para correo saliente | contiene las configuraciones del sistema |
|------|------|------|
| home | operativos: directorio para usuario operativos | directorio que tiene cada usuario para almacenar sus documentos… |
|------|------|------|
| lib | kdb: contiene varios keymaps | imágenes de librería que el sistema necesita (muy importante) |
|------|------|------|
| proc | fb: dispositivos de Frame Buffer | tiene información de los procesos que están corriendo actualmente |
|------|------|------|
| root | pg19033.txt | todos los archivos del usuario root |
|------|------|------|
| srv | cvs: datos relacionados con CVS | datos relacionados con servicios de servidor |
|------|------|------|
| mnt | cdrom | directorio para montar sistemas de archivos |
|------|------|------|
| opt | - | espacio para uso de software externo |
|------|------|------|
| media | cdrom: lugar para montar datos de CD-ROM | datos relacionados con servicios de servidor |
|------|------|------|
| sys | drivers: contiene un directorio para cada driver de cada dispositivo que es cargado en devices | muestra información relacionada con los subsistimos del kernel, hardware, y drivers |
|------|------|------|
| tmp | yum.log: logs del yum install | contiene archivos temporales |
|------|------|------|
| usr | lib: tiene las librerías de los programas | aplicaciones y herramientas de los usuarios |
|------|------|------|
| var | cache: almacena datos guardados en cache | archivos variables que pueden crecer |
|------|------|------|


### 2.
| Comando   | Usuario | Descripción   |
|------|------|------|
| tac file1 | root | ver el contenido de un archivo (file1) desde la primera linea |
|------|------|------|
| gzip file1 | operativos | comprime el archivo (file1) |
|------|------|------|
| lsattr | root | mostrar atributos especiales |
|------|------|------|
| whereis abc | operativos | muestra la ubicación del archivo (abc) |
|------|------|------|
| cp file1 | root | copia el archivo (file1) |
|------|------|------|
| rm -f file1 | root | borra el archivo (file1) |
|------|------|------|
| rmdir dir1 | operativos | borra el directorio (dir1) |
|------|------|------|
| iconv -l | root | lista de cifrados conocidos |
|------|------|------|
| df -h | root | muestra una lista de las particiones montadas |
|------|------|------|
| dpkg -l | root | mostrar todos los paquetes deb instalados en el sistema |
|------|------|------|



### 3. El comando printenv imprime los valores de las variables de ambiente (todas o la que se especifique). Evidencia: https://www.dropbox.com/sh/wmulxcpkql3r4th/AACEXyOlApUMHyiBnxDFf8i4a?dl=0

## Referencias
* https://github.com/ICESI/so-commands/tree/master/centos7
* https://www.computerhope.com/unix/printenv.htm
* http://www.tldp.org/LDP/Linux-Filesystem-Hierarchy/html/
* http://www.thegeekstuff.com/2010/09/linux-file-system-structure/?utm_source=tuicool
* https://blog.desdelinux.net/mas-de-400-comandos-para-gnulinux-que-deberias-conocer/


