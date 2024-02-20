## Configuración de proftpd para usuarios anónimos.
### Configura proftpd para que los usuarios accedan al directorio /home/ftp (puedes usar DefaultChdir). ¿Cual es la diferencia entre DefaultRoot y DefaultChdir?
La diferencia entre ambas configuraciones es la siguiente:
  - DefaultRoot se usa para establecer la ruta por defecto cuando se conecte el usuario al servidor ftp.
  - DefaultChdir se usa para establecer la ruta a la que se cambiará al usuario una vez conectado.
