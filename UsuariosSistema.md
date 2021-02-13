# Acceso de los usuarios del sistema al servidor FTP

## En esta práctica modificaremos la configuración para que los usuarios del sistema puedan acceder a nuestro servidor

## Pasos:

### 1.- Creamos en el servidor un usuario llamado Juan

### 2.- Creamos su directorio de trabajo

![6.png](https://github.com/Juanrdls/VSFTPD/blob/main/Capturas/6.PNG)

### 3.- Cambiamos el propietario del directorio

![7.png](https://github.com/Juanrdls/VSFTPD/blob/main/Capturas/7.PNG)

### 4.- Configuración del fichero vsftpd.conf

#### Deshabiitar Ipv6 y activar Listen

![8.png](https://github.com/Juanrdls/VSFTPD/blob/main/Capturas/8.PNG)

#### Descomentar la siguiente líena:

![9.png](https://github.com/Juanrdls/VSFTPD/blob/main/Capturas/9.PNG)

#### Quitar permisos de escritura al directorio del usuario

![10.png](https://github.com/Juanrdls/VSFTPD/blob/main/Capturas/10.PNG)

### 5.- Comprobación

![11.png](https://github.com/Juanrdls/VSFTPD/blob/main/Capturas/11.PNG)
