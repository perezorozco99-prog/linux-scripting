| **`/`** | **Directorio raíz.** El punto de partida del sistema de archivos. Contiene todos los demás directorios y archivos. 

| **`/bin`** | **Binarios esenciales.** Archivos ejecutables fundamentales para el arranque y comandos básicos del sistema (`ls`, `cp`, `mv`). 

| **`/boot`** | **Archivos de arranque.** Contiene el núcleo (*kernel* de Linux), la configuración de GRUB y ficheros necesarios para iniciar la máquina. 

| **`/dev`** | **Dispositivos (*devices*).** Representación de hardware como archivos especiales (discos duros, particiones, puertos USB). 

| **`/etc`** | **Configuraciones del sistema.** Archivos de texto que controlan el comportamiento de programas y servicios (redes, usuarios, `crontab`). 

| **`/home`** | **Directorios personales.** Espacio de trabajo de cada usuario estándar (por ejemplo, `/home/usuario`), donde guarda sus documentos y configuraciones personales. 

| **`/lib` / `/lib64`** | **Bibliotecas compartidas.** Contienen los archivos `.so` necesarios para que los programas funcionen (`/lib` para 32 bits, `/lib64` para 64 bits). 

| **`/media`** | **Montaje de medios extraíbles.** Punto de montaje automático para discos externos, memorias USB o CD-ROM. 

| **`/opt`** | **Software opcional.** Directorio reservado para software adicional o de terceros que no forma parte de la distribución base. 

| **`/tmp`** | **Archivos temporales.** Espacio para datos volátiles usados temporalmente por aplicaciones; se limpia habitualmente en cada reinicio. 

| **`/usr`** | **Recursos del usuario (*Unix System Resources*).** Contiene binarios (`/usr/bin`), librerías (`/usr/lib`) y documentación de programas instalados. 

| **`/var`** | **Datos variables.** Archivos que cambian dinámicamente de tamaño, como registros del sistema (*logs* en `/var/log`), colas de correo y bases de datos. 
