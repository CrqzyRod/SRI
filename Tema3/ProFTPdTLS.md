### Lee el artículo anterior y configura proftp para acceso seguro mediante TLS

Descarga de openssl

![imagen](https://github.com/CrqzyRod/SRI/assets/122454007/7bbeced9-0913-47ee-8574-cdda21d8c691)

Generamos el certificado

![imagen](https://github.com/CrqzyRod/SRI/assets/122454007/5dbbb367-a60f-423d-83d9-cb4472300d7f)

Descomentamos la línea en la cuál se incluyen los certificados ssl para proftpd

![imagen](https://github.com/CrqzyRod/SRI/assets/122454007/1e1f2de5-76da-4232-ada4-493e55988768)

### Crea un usuario del sistema

Creamos el usuario usando el comando adduser

![imagen](https://github.com/CrqzyRod/SRI/assets/122454007/757bc4ff-4dc4-466f-8b39-06e957fd6734)

### Instala filezilla

Lo descargamos usando el comando apt-get install filezilla

![imagen](https://github.com/CrqzyRod/SRI/assets/122454007/440bb584-e626-4664-bbb4-a28dcaa633fd)

### Configura filezilla para usar una conexión TLS y comprueba que funciona correctamente.

