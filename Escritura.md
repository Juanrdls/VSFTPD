# Accedemos al servidor FTP con anonymous el cual tiene permiso de escritura en su directorio
sugerencia el cual es un subdirectorio de su diretorio raiz.

Configuramos el servidor para que Anonymous pueda escribir solo en /sugerencias

## Pasos:

### 1.- Realizamos los siguientes comandos:

![16.png](https://github.com/Juanrdls/VSFTPD/blob/main/Capturas/16.PNG)

### 2.- Configuramos el archivo vsftpd.conf para que quede de la siguiente forma:

![17.png](https://github.com/Juanrdls/VSFTPD/blob/main/Capturas/17.PNG)

### 3.- Comprobación:

#### Subir:

![18.png](https://github.com/Juanrdls/VSFTPD/blob/main/Capturas/18.PNG)

#### Descargar:

![19.png](https://github.com/Juanrdls/VSFTPD/blob/main/Capturas/19.PNG)

### 4.- Comprobación en el directorio raiz:

![20.png](https://github.com/Juanrdls/VSFTPD/blob/main/Capturas/20.PNG)
