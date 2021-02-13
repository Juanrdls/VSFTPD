# Accedemos al servidor FTP con anonymous el cual tiene permiso de escritura en su directorio
sugerencia el cual es un subdirectorio de su diretorio raiz.

Configuramos el servidor para que Anonymous pueda escribir solo en /sugerencias

## Pasos:

### 1.- Realizamos los siguientes comandos:

![16.png]()

### 2.- Configuramos el archivo vsftpd.conf para que quede de la siguiente forma:

![17.png]()

### 3.- Comprobación:

#### Subir:

![18.png]()

#### Descargar:

![19.png]()

### 4.- Comprobación en el directorio raiz:

![20.png]()
