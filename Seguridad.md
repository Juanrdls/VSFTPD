# Seguridad

## En este apartado procederemos a instalar un certificado para que nuestro servidor sea seguro

### Pasos:

### 1.- Instalar el paquete que utilizaremos para generar el certificado:

![29.png](https://github.com/Juanrdls/VSFTPD/blob/main/Capturas/29.PNG)

### 2.- Generar el certificado:

![30.png](https://github.com/Juanrdls/VSFTPD/blob/main/Capturas/30.PNG)

### 3.- Configurar el fichero vsftpd.conf:

![31.png](https://github.com/Juanrdls/VSFTPD/blob/main/Capturas/31.PNG)

### 4.- Riniciamos el servidor: ``` systemctl restart vsftpd.service ```

### 5.- Nos conectamos de la siguiente forma:

![32.png](https://github.com/Juanrdls/VSFTPD/blob/main/Capturas/32.PNG)

![33.png](https://github.com/Juanrdls/VSFTPD/blob/main/Capturas/33.PNG)

#### Observamos que nos aparece un candado lo que nos indica que ha funcionado el certificado.
