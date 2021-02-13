# Usuarios Virtuales

## En este apartado crearemos usuarios virtuales para que se puedan conectar a nuestro servidor

## Pasos Previos:

``` apt install apache2-utils ```

``` apt install libpam-pwdfile ```

## Pasos:

### 1.- Configuramos el fichero vsftpd.conf para que nos quede de la siguiente forma:

![38.png](https://github.com/Juanrdls/VSFTPD/blob/main/Capturas/34.PNG)

### 2.- Creamos una carpeta donde guardaremos la lista de usuarios:

![39.png](https://github.com/Juanrdls/VSFTPD/blob/main/Capturas/35.PNG)

### 3.- Dentro del directorio /etc/pam.d configuramos el archivo vsftpd para que nos quede de la siguiente forma

![40.png](https://github.com/Juanrdls/VSFTPD/blob/main/Capturas/36.PNG)

### 4.- Creamos el usuario virtual

![41.png](https://github.com/Juanrdls/VSFTPD/blob/main/Capturas/37.PNG)

### 5.- Creamos el directorio y entramos en el

![42.png](https://github.com/Juanrdls/VSFTPD/blob/main/Capturas/38.PNG)

### 6.- Creamos el archivo de configuración por cada usuario creado

![43.png](https://github.com/Juanrdls/VSFTPD/blob/main/Capturas/39.PNG)

### 7.- Creamos la ruta donde podrá acceder dicho usuario

![44.png](https://github.com/Juanrdls/VSFTPD/blob/main/Capturas/40.PNG)

### 8.- Comprobaciones
