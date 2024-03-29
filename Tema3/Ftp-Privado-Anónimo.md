## Configuración de proftpd para usuarios anónimos.
### Configura proftpd para que los usuarios accedan al directorio /home/ftp (puedes usar DefaultChdir). ¿Cual es la diferencia entre DefaultRoot y DefaultChdir?

En el fichero de configuración de proftpd establecemos la directiva DefaultRoot para establecer el directorio por defecto de los usuarios que accedan.

![imagen](https://github.com/CrqzyRod/SRI/assets/122454007/1b9f47df-df63-4d73-b59c-13605465bcfb)

La diferencia entre ambas configuraciones es la siguiente:
  - DefaultRoot se usa para establecer la ruta por defecto cuando se conecte el usuario al servidor ftp.
  - DefaultChdir se usa para establecer la ruta a la que se cambiará al usuario una vez conectado.

### No se permitirá subir ni eliminar nada de la carpeta ftp

En el fichero de configuración de proftpd usando la directiva Directory establecemos el parámetro Limit WRITE para limitar la escritura en ese fichero y así inutilizamos la subida y bajada de ficheros.

![imagen](https://github.com/CrqzyRod/SRI/assets/122454007/9564aad0-303d-47de-aadd-5ea9fa30f08b)

### Configura el acceso mediante usuario anónimo

Para ello en el fichero de configuración de proftpd descomentamos las líneas de configuración de anonymous.

![imagen](https://github.com/CrqzyRod/SRI/assets/122454007/7a857696-7cf0-45c5-af99-602af26ed25c)

### Permite que el usuario anónimo pueda escribir si accede desde la red 10.4.0.x

Para ello permitimos la conexión usando la directiva AllowUser

![imagen](https://github.com/CrqzyRod/SRI/assets/122454007/b8afe7e3-445b-4b8a-9f04-363ae45e9eec)

Comprobación accediendo con IP:10.4.0.43 

![imagen](https://github.com/CrqzyRod/SRI/assets/122454007/a3b88ff5-f767-42de-b327-2ce154f41ea8)

Comprobación accediendo con IP:
