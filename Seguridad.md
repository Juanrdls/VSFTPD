# Seguridad

## En este apartado procederemos a instalar un certificado para que nuestro servidor sea seguro

### Pasos:

### 1.- Instalar el paquete que utilizaremos para generar el certificado:

![29.png]()

### 2.- Generar el certificado:

![30.png]()

### 3.- Configurar el fichero vsftpd.conf:

![31.png]()

### 4.- Riniciamos el servidor: ``` systemctl restart vsftpd.service ```

### 5.- Nos conectamos de la siguiente forma:

![32.png]()

![33.png]()

#### Observamos que nos aparece un candado lo que nos indica que ha funcionado el certificado.
